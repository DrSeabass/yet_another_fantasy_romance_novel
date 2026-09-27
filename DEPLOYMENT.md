# GitHub Pages deployment

The site is configured for **https://yafn.jordanthayer.com**.

## Repository configuration

- `.github/workflows/deploy.yml` is copied from `adventures_of_dee`. Every push to `main` builds `content/` into `public/` using Node 24, then deploys the artifact to GitHub Pages. It also supports manual runs.
- `quartz.config.yaml` sets the site title, `baseUrl: yafn.jordanthayer.com` (no protocol or trailing slash), and the footer repository link. Its remaining settings come from this repository's Quartz defaults.
- `content/index.md` is the homepage. Add the novel's Markdown pages under `content/`.
- The workflow grants `contents: read`, `pages: write`, and `id-token: write`, and deploys through the `github-pages` environment. No custom deployment secret is required.
- The CNAME plugin generates `public/CNAME` from `baseUrl`. GitHub Actions deployments still require setting the custom domain in GitHub's Pages settings; the generated file does not configure it.
- `deploy-v5.yaml` and `deploy-preview.yaml` are inherited Cloudflare workflows restricted to `jackyzha0/quartz`; they do not deploy this repository.

## GitHub and DNS setup

1. Open https://github.com/DrSeabass/yet_another_fantasy_romance_novel/settings/pages and select **GitHub Actions** as the build and deployment source.
2. Set the Pages custom domain to `yafn.jordanthayer.com` and save.
3. At the DNS provider for `jordanthayer.com`, create a **CNAME** record named `yafn` targeting `drseabass.github.io` (no protocol or repository path).
4. Enable **Enforce HTTPS** in Pages settings once GitHub has provisioned the certificate.
5. Set the repository's default branch to `main` if it is still `v5`. Under Settings → Environments → github-pages, ensure any deployment branch restrictions allow `main`.
6. Commit and push the configuration to `main`. Watch the **Deploy website** workflow in Actions, then check https://yafn.jordanthayer.com.

GitHub CLI was not authenticated during migration, so these remote settings have not been verified or changed.

## Local validation

```sh
npm ci
npx quartz plugin install
npx quartz build
```

The current configuration uses npm plugins installed by `npm ci`. With no Git plugin lockfile, `quartz plugin install` reports that no `quartz.lock.json` exists and exits successfully. If Git-based plugins are added later, generate and commit the plugin lockfile as well.

The generated site is in `public/` and is ignored by Git. Confirm that `public/index.html` exists and that `public/CNAME`, `public/sitemap.xml`, and `public/index.xml` use the intended domain.

References: [GitHub Pages custom workflows](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages), [custom domain setup](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

# k61.dev

[![deploy](https://img.shields.io/github/actions/workflow/status/kurtzeborn/k61.dev/deploy.yml?label=deploy)](https://github.com/kurtzeborn/k61.dev/actions/workflows/deploy.yml)

Landing page for k61.dev projects, deployed to www.k61.dev.

## Projects

- [URL Shortener](https://url.k61.dev) - Fast, free URL shortener with analytics ([source](https://github.com/kurtzeborn/url-shortener))

## Development

```bash
npm install
npm run dev
```

## Deployment

Automatic via GitHub Actions on push to `main`.

Requires secret: `AZURE_STATIC_WEB_APPS_API_TOKEN`

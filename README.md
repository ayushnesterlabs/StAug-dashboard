# Augustine HR-OPS — Entity Model Explorer

A single-page, fully self-contained dashboard for exploring the Augustine HR-OPS entity model. All diagrams and assets are embedded inline — no build step, no external dependencies.

## Deploy on Vercel

This is a static site; Vercel serves `index.html` directly with no framework or build configuration.

1. Go to [vercel.com/new](https://vercel.com/new) and import this repository.
2. Leave **Framework Preset** as **Other** and all build settings empty.
3. Click **Deploy**.

Or with the Vercel CLI:

```sh
npx vercel --prod
```

## Local preview

```sh
npx serve .
```

Then open http://localhost:3000.

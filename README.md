# MicroLoan Tracker

MicroLoan Tracker is a mobile-first financial management prototype for small vendors. It tracks loans, repayments, daily sales, expenses, repayment schedules, reports, and planning simulations.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Deploy

This is a Vite application and is ready to deploy from GitHub on Vercel:

1. Import `https://github.com/Lazycode66/loan`.
2. Keep the detected framework as **Vite**.
3. Use `npm run build` as the build command.
4. Use `dist` as the output directory.

The same build command and output directory work for Netlify and other static hosts.

The current prototype persists demo and user-entered records in browser `localStorage`. No secrets or environment variables are required for the current build.

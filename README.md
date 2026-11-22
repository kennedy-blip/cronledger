# CronLedger

Scheduled job monitor, overlap guard, and execution-history ledger. Built with Vite, React, TypeScript, Tailwind CSS v4, and Vercel Functions.

## Development

```bash
npm install
npm run dev
```

For API routes locally, use `npm run dev:vercel` (`vercel dev`). The Vite-only dev server falls back to seeded demo data when the API is unavailable.

## Production

Import this repository into Vercel. The frontend builds with `npm run build`; API handlers live in `/api`.

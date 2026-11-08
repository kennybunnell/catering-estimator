# Catering Estimator

Premium catering estimate demo built with Next.js 15, React 19, and Supabase.

## Run locally

```bash
npm install
npm run dev
```

## Deploy

Import this GitHub repository into Vercel (Next.js framework). The estimator works without a database; quote submissions require Supabase.

1. Create a Supabase project and execute `supabase.sql` in its SQL editor.
2. Set `SUPABASE_URL` and `SUPABASE_SERVICE_ROLE_KEY` in Vercel environment variables (server-side only).
3. Redeploy and test a quote submission.

## Important

The Gather & Grace name and all prices are placeholders. Edit `lib/pricing.ts` for real rates and profit targets. Add rate limiting, spam protection, a privacy notice, and verified brand assets before public lead collection. No admin dashboard or automated email is included yet.
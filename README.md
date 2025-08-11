# CoreIQ Scorer (v1.4.1)

## Setup
1) Copy `.env.example` to `.env.local` and fill your Supabase URL + anon key.
2) `npm i`
3) `npm run dev`

## Deploy (Vercel)
- Add env vars in Vercel: `NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`.
- Include your Vercel preview and prod domains in Supabase Auth Redirect URLs.

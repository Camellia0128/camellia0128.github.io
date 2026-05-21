# Vault Platform Sync

This branch keeps the deployed Vault Platform project without overwriting the current main-site homepage.

## Live URLs
- Frontend: https://vault-platform-nine.vercel.app
- Admin: https://vault-platform-nine.vercel.app/admin

## Current status
- Vercel deployment is live.
- The site is still running in demo mode for data features.
- Real Supabase production credentials have not been connected in this session.

## What is pending
These environment variables are still required before real registration, login, file upload, and persistent admin settings can work:
- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`
- `SUPABASE_SERVICE_ROLE_KEY`

## Notes
- The current GitHub main branch homepage was left untouched.
- This branch is a safe sync branch for the Vault Platform work.

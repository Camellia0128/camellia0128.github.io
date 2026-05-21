# Supabase Setup Checklist

## Purpose
Use Supabase for:
- user registration and sign-in
- password reset
- Postgres data storage
- file storage
- admin-side persistent settings

## Required values
Fill these values into Vercel project environment variables:
- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`
- `SUPABASE_SERVICE_ROLE_KEY`

## Database step
Run the initial SQL migration from the project file:
- `supabase/migrations/20260521_init.sql`

## Storage buckets
Create these buckets:
- `vault-files`
- `avatars`

## Auth settings
Enable:
- Email/password sign-in
- Email confirmation
- Password reset email

## Current blocker
A real Supabase project was not provisioned in this session, so the production deployment is still not connected to live auth, storage, and database services.

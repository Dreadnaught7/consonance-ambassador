# Consonance Ambassador Frontend

Isolated static presentation layer for the Consonance Ambassador System, branded as **Consonance Compass** under EJFinkley Holdings.

## Cloudflare Pages
- Production branch: `main`
- Framework preset: `None`
- Build command: leave blank (or `exit 0`)
- Build output directory: `public`
- Pages project: `consonance-ambassador`

## Architecture
QR/redirect -> Cloudflare Pages -> Supabase `ambassador-intake` Edge Function -> protected Supabase tables.

No authoritative business data is stored in this frontend.

## Identity
The master Consonance mark, palette and usage doctrine are documented in `BRAND.md`. Referral provenance is represented as a functional verified state without exposing internal attribution identifiers.
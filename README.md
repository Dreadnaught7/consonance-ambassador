# Consonance Ambassador Frontend

Isolated static presentation layer for the Consonance Ambassador System.

## Cloudflare Pages
- Production branch: `main`
- Framework preset: `None`
- Build command: leave blank (or `exit 0`)
- Build output directory: `public`

## Architecture
QR/redirect -> Cloudflare Pages -> Supabase `ambassador-intake` Edge Function -> protected Supabase tables.

No authoritative business data is stored in this frontend.

# Beacon of Light Live Venue Booking

Next.js + Supabase live booking app.

## Run locally
1. `npm install`
2. `npm run dev`

## Admin account
In Supabase Dashboard go to Authentication > Users > Add user and create:
`beaconoflightoasis@gmail.com`
with your own strong password.

## Deploy
Import this folder/repository into Netlify or Vercel and set:
- NEXT_PUBLIC_SUPABASE_URL
- NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY

The public booking form submits through the `submit_booking` RPC created by `beacon_supabase_setup.sql`.

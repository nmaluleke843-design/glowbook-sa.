# GlowBook SA

Salon booking marketplace prototype. Clients book a salon service and pay a 15% deposit online
(GlowBook's commission). The salon collects the remaining 85% at the salon.

## Run on GitHub Pages
1. Create a repository (for example `glowbook-sa`) and upload `index.html` and this README.
2. Settings > Pages > Deploy from a branch > `main` / root.
3. Your site is at `https://<your-username>.github.io/glowbook-sa/`.

## Current limits
- Demo mode: bookings and salons are stored in each visitor's browser only.
- Payments are simulated.

## To go live with real customers
- Backend for shared data and logins (Supabase is a good fit).
- Payment provider that takes the deposit (PayFast or Yoco) and pays out the salon.
- Salon verification and WhatsApp or SMS booking confirmations.

# Hey, I'm Sunday Omena Anderson 👋

I build and ship web and mobile products end-to-end  React and React Native on the front, NestJS APIs on the back, and the servers they run on.

Currently at **Xavier Paisley**, where I've shipped live products across health insurance, fuel delivery, and real estate. On the side I build, ship, and operate my own — including [PitchPlay](https://pitchplay24.com), a live football competition management SaaS.

---

## 🏗 My own products

| Product | What it is | Stack | Status |
|---|---|---|---|
| [PitchPlay](https://pitchplay24.com) · [organizer dashboard](https://app.pitchplay24.com) | Football competition management SaaS — organizer dashboard plus a public fan-facing side for live competitions | NestJS · TypeScript · Supabase (RLS) · Redis · Socket.io · React · React Native | ✅ Live |

Built from the architecture up: an organizer/fan module split, real-time event broadcasting over Socket.io, and a NestJS caching layer backed by Redis that absorbs fan traffic instead of passing it through to Supabase.

The fan side is open — no login needed. If you want to see the organizer side, sign up on the dashboard and create a competition; it's free and takes a minute.

---

## 🚀 Shipped at Xavier Paisley

| Product | What it is | Stack | Status |
|---|---|---|---|
| [RentSell](https://rentsell.net) | Verified real estate brokerage platform | Next.js · Supabase · Sanity | ✅ Live |
| [HealthSure](https://app.healthsure.co) | Health insurance & HMO access platform | React · TypeScript | ✅ Live |
| [FuelRescue](https://fuel-rescue.com) | On-demand fuel delivery app + admin dashboard | React Native · NestJS · PostgreSQL · Docker | ✅ On stores |

---

## 🤝 Contract work

| Product | What it is | What I did | Status |
|---|---|---|---|
| [ScoutMate](https://scoutmate.pro) | Pitch-booking platform — players find and book synthetic pitches, organise matches among themselves, and pay for the slot | Rebuilt the backend and took the app through to store release | ✅ Live on Google Play & App Store |

Brought in to get a stalled mobile app out the door. I revamped the NestJS backend and re-deployed the stack API, MongoDB, and Redis in Docker Compose on a Hetzner VPS I provision and maintain, with uploads offloaded to S3 then handled the Google Play and App Store submissions end to end.

---

## 🛠 What I work with

**Frontend & Mobile**
React · React Native · Next.js · TypeScript · Tailwind CSS · Redux · Expo

**Backend & Data**
NestJS · Node.js · Express · PostgreSQL · MongoDB · Redis · Socket.io · Supabase (RLS) · Sanity CMS · REST APIs

**Infrastructure & Deployment**
Docker · Docker Compose · Linux VPS (Hetzner) · GitHub Actions · Cloudflare (DNS/SSL) · AWS (EC2, S3) · App Store & Google Play releases

**Integrations**
Paystack (including Dedicated Virtual Accounts & Transfers) · Stripe webhooks

---

## 🔧 Beyond the code

I don't hand my apps off to a platform and hope for the best. I run them.

- Provision and harden Linux VPSs myself  SSH key management, firewall rules, dedicated deploy users, no control panel in between.
- Run multi-service stacks in Docker Compose: NestJS API, self-hosted PostgreSQL or MongoDB, and Redis, with data on attached volumes and uploads offloaded to S3.
- Host multiple products off shared database infrastructure, each with its own isolated database.
- Ship on push with GitHub Actions, behind Cloudflare DNS and SSL.

Which means I can take a product from a Figma file to an app store listing and a production server without needing anyone else in the loop.

---

## 📌 Pinned repos worth looking at

- **[hrms-system](https://github.com/Sosaristic/hrms-system)** — HR management system frontend
- **[hrms-system-backend](https://github.com/Sosaristic/hrms-system-backend)** — HR management system backend

---

## 📫 Reach me

- Email: sundayomena9@gmail.com
- Open to remote freelance, contract, and full-time roles

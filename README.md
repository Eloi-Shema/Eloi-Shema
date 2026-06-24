![header](./header.svg)

Email: [build@eloishema.dev](mailto:build@eloishema.dev)

## LIVE PROJECTS

### [Trapeloi](https://trapeloi.com) - Beat Store

A music licensing platform I designed, built and maintain solo. A producer upload beats; buyers purchase a lifetime license and download them. No subscriptions, no leases, one payment, full ownership.

<table>
  <tr>
    <td><a href="https://trapeloi.com"><img src="./assets/trapeloi-1.png" width="380" alt="Trapeloi homepage"/></a></td>
    <td><a href="https://trapeloi.com"><img src="./assets/trapeloi-2.png" width="380" alt="Trapeloi beat listing"/></a></td>
  </tr>
</table>

**What's under the hood:**
- Auth via `better-auth` sessions, email verification, OAuth flows
- Bot & abuse protection via `Arcjet`.
- Beat files served from `Cloudflare R2` via signed URLs with access control
- Payments and licensing through `LemonSqueezy`
- Error monitoring via `Sentry` with custom alerting for any server side error
- Transactional email via `Brevo`.

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![LemonSqueezy](https://img.shields.io/badge/LemonSqueezy-FFD700?style=for-the-badge&logoColor=black)
![BetterAuth](https://img.shields.io/badge/better--auth-111827?style=for-the-badge&logoColor=white)
![Upstash](https://img.shields.io/badge/Upstash_Redis-c93131?style=for-the-badge&logoColor=black)

---

### [Zone7](https://zone7.rw) - Real Estate Platform

Delivered as a paid freelance contract. A full property browsing and management platform, listings with search and filtering, plus an admin dashboard for managing properties, users, and inquiries.

<table>
  <tr>
    <td><a href="https://zone7.rw"><img src="./assets/zone7-1.png" width="380" alt="Zone7 property listings"/></a></td>
    <td><a href="https://zone7.rw"><img src="./assets/zone7-2.png" width="380" alt="Zone7 property detail"/></a></td>
  </tr>
</table>

**Architecture highlights:**
- Role-based access control (User / Broker / Admin) built on `NextAuth.js` with custom JWT extensions, refresh token rotation, concurrency protection, device tracking
- Rate limiting middleware on sensitive API routes
- Image management via `Cloudinary`
- Email notifications via `Brevo`

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

### [Wedding Photo App](https://wedding.eloishema.dev) - Shipped for a Live Marriage Event

A mobile-first photo-sharing app for a wedding. Guests scan a QR code, open in browser, upload photos, no app install needed. Gallery auto-refreshes every 30 seconds. Built, deployed, and running on the day.

<table>
  <tr>
    <td><a href="https://wedding.eloishema.dev"><img src="./assets/wedding-1.png" width="380" alt="Wedding app upload screen"/></a></td>
  </tr>
</table>

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## Core Stack

<table>
  <tr>
    <td><strong>Frontend</strong></td>
    <td>Next.js (App Router), React, TypeScript, Tailwind CSS</td>
  </tr>
  <tr>
    <td><strong>Backend</strong></td>
    <td>Node.js, PostgreSQL, Prisma, MongoDB, Mongoose</td>
  </tr>
  <tr>
    <td><strong>Auth</strong></td>
    <td>better-auth, NextAuth.js</td>
  </tr>
  <tr>
    <td><strong>Storage</strong></td>
    <td>Cloudflare R2, Cloudinary</td>
  </tr>
  <tr>
    <td><strong>Payments</strong></td>
    <td>LemonSqueezy</td>
  </tr>
  <tr>
    <td><strong>Infra</strong></td>
    <td>Vercel, Neon, Upstash Redis</td>
  </tr>
  <tr>
    <td><strong>Observability</strong></td>
    <td>Sentry, Brevo</td>
  </tr>
  <tr>
    <td><strong>Security</strong></td>
    <td>Arcjet, rate limiting middleware, refresh token rotation</td>
  </tr>
  <tr>
    <td><strong>Learning</strong></td>
    <td>Go, modern backend services and CLI tooling</td>
  </tr>
</table>

---

## About

Self-taught full-stack developer working independently, client contracts and my own products. I take projects from architecture to production and keep them running.

<details>
<summary><strong>Production incidents I've diagnosed and resolved</strong></summary>

<br/>

These aren't case studies — they're from maintaining a live platform:

- **Arcjet false positives**: Rwanda traffic routed through a Cloudflare Johannesburg PoP was triggering bot detection. Traced the IP reputation issue and configured Arcjet rules accordingly.
- **better-auth silent breakage**: An unintended `npm audit fix` upgraded `better-auth` to a breaking version. Identified from the diff, pinned the version, added lockfile discipline going forward.
- **Brevo 401 in production**: Transactional emails stopped after Vercel rotated serverless IPs. Diagnosed from Sentry logs, updated Brevo's IP allowlist.
- **Sentry alert misconfiguration**: Alerts were firing on already-resolved errors. Fixed by correcting issue grouping rules and alert condition logic.

</details>

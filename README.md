## Hi, I'm Julian 👋

**Senior Frontend / Full Stack Engineer · React · TypeScript · Node.js · Offline-first PWAs**
Glasgow, UK · Open to remote (UK) or hybrid in Glasgow / Edinburgh

Senior software engineer with 10+ years in the industry and 7+ years of React. For four years I was a senior frontend engineer on Motors.co.uk / Cazoo, a UK car marketplace with 500–700k monthly users. 

**Recent highlights**

- Designed, built and run Form:at alone, an offline-first PWA on Cloudflare in production: 500+ commits since May 2026.
- Upgraded the Motors.co.uk monolith (ASP.NET + React) from React 17 to 19, in two phases.
- Replaced Redux entirely with Zustand (16 domain slices, ~240 files), documented the new store for the team, then adopted the React Compiler.
- Moved analytics to GA4 across both web apps, with the Next.js app's tracking rebuilt on a single data layer.

---

## Featured project

### [Form:at](https://github.com/Zitric/form-at) · [formatglasgow.com](https://formatglasgow.com)

PWA for a Glasgow techno collective. Its recorded sets are 90-minute mixes of 100–220MB, and you can save them to your phone and play them on the Glasgow Subway with no signal. Most of the architecture exists to serve that.

- **Offline audio:** IndexedDB with a storage-quota pre-flight, and a custom service worker that serves HTTP Range requests so seeking works offline. Lock-screen playback through the Media Session API.
- **Full stack on Cloudflare:** TanStack Start (React 19) on Pages/Workers, D1 (SQLite) for the catalogue and analytics, R2 for audio with versioned immutable keys, presigned direct-to-R2 uploads for 220MB files, and Web Push sent from Workers.
- **Admin dashboard** behind Cloudflare Access, with server-side JWT verification on every write endpoint.
- **Monorepo:** pnpm + Turborepo, a shared design system (Storybook, Chromatic visual tests), Vitest and Playwright on Chromium and WebKit, CI/CD on GitHub Actions. Built AI-assisted with Claude Code under a written agent working agreement (CLAUDE.md).

`TypeScript` `React 19` `TanStack Start` `Cloudflare Workers` `D1` `R2` `Service Worker` `IndexedDB` `Vitest` `Playwright`

---

## Currently learning

Building with LLMs. I'm working through Anthropic's Claude Academy courses, starting with Claude Code (Claude Code 101 done), then agents, MCP and the Claude API.

## Stack

**Frontend** &nbsp; React · Next.js · TypeScript · Zustand · Redux · React Native · Tailwind CSS · Storybook

**Web platform** &nbsp; PWA · Service Workers · IndexedDB · Web Push · Media Session API · Core Web Vitals

**Backend & cloud** &nbsp; Node.js · Cloudflare (Workers, Pages, D1, R2) · AWS (Lambda, API Gateway, S3, Cognito) · MongoDB · REST

**Testing** &nbsp; Vitest · Jest · React Testing Library · Playwright · Cypress

**Tooling** &nbsp; pnpm · Turborepo · GitHub Actions · Biome · Sentry

**Analytics** &nbsp; GA4 · GrowthBook · feature flags

**Certified** &nbsp; Anthropic: Claude Code 101 · Microsoft: Azure Fundamentals

---

## Open to work

Senior frontend or full-stack roles. Remote in the UK, or hybrid in Glasgow / Edinburgh. Settled status, no sponsorship needed.

[LinkedIn](https://www.linkedin.com/in/julianpalomodeonis) · [formatglasgow.com](https://formatglasgow.com)


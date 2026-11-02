# Arman Naseri Far

**Software developer building AI tools and full-stack web apps**  
Computer Engineering student at Politecnico di Torino · Turin, Italy

[Email](mailto:arman.naserfar@yahoo.com) · [LinkedIn](https://www.linkedin.com/in/arman-naseri-far-5773b3341/) · [GitHub](https://github.com/Armannss)

## Summary

I build products end to end, from the database and API to the interface and deployment. My work includes a Persian personal-growth platform, an open-source tool for AI coding agents, an online shop with an AI assistant, and a real-time VR rehearsal system built with a team.

## Skills

- **Languages:** TypeScript, JavaScript, C#, Python, SQL, HTML, CSS
- **Web:** Next.js, React, Tailwind CSS, Node.js, Fastify, Progressive Web Apps, RTL interfaces
- **Data:** PostgreSQL, Prisma, Drizzle
- **AI:** Claude API with tool use, Claude Code plugins, agent workflows
- **Real-time and VR:** WebRTC, WebSocket, Web Push, Unity, Meta Quest, WebGL
- **Tools:** Git, GitHub Pages, Vercel, Docker

## Projects

### NEXTRIBE
**Creator and developer** · Oct 2026 to present  
[Website](https://nextribe.app/welcome) · [App preview](https://nextribe.app/welcome#inside-app) · [Case study](https://github.com/Armannss/Armannss/blob/main/projects/nextribe/README.md) · Private source

A Persian, mobile-first personal-growth platform: a public website plus a web app members install from the browser.

- Built daily missions across six life areas, planning, progress charts, personal tools and a tribe leaderboard ranked by progress toward each member's own goal.
- Added a safety step in onboarding that hides unsuitable missions, and kept mood, journal and safety answers out of anything the tribe can see.
- Built member administration, personal Web Push reminders and a Telegram bot for membership applications.
- Scale: 228 commits, 71 pages, 19 API routes and 77 database models.

*Next.js, React, TypeScript, Tailwind CSS, PostgreSQL, Prisma, Web Push, Claude API*

### armap
**Creator** · Oct 2026  
[Repository](https://github.com/Armannss/armap) · MIT license

A Claude Code plugin that gives the agent a compact, ranked map of a codebase at the start of each session, so it opens the right files first.

- Recognizes around 50 file types and resolves imports to real files for 15 languages, with no compiler or language server.
- Ranks files with PageRank over their dependency graph and prints the top results within a token budget.
- Added `deps` and `refs` queries the agent can run instead of searching and reading whole files.
- In a small pilot (one project, five questions, two runs each), total tokens fell 20%. Multi-step questions saved 35% to 48%; simple lookups cost 2% to 5% more.

*JavaScript, Node.js, no runtime dependencies*

### Parsilon Part
**Creator and developer** · May 2026 to Oct 2026  
[Repository](https://github.com/Armannss/Parsilon-web-application-mobile-shell)

A mobile-first online shop for auto parts, with an admin panel and an AI parts assistant.

- Built the AI assistant on the Claude API with tool use. It searches the live catalogue, checks price and stock, and shows matching parts as cards. It has read-only access, so it cannot place orders or see accounts.
- Built search, filters, product pages with compatible cars, cart, checkout, order tracking and wholesale requests.
- Built the admin panel for products, orders, wholesale requests and sales reports.

*Next.js, React, TypeScript, Tailwind CSS, PostgreSQL, Prisma, Claude API*

### MEVO / Director
**Team project with Matteo and Leonardo** · Oct 2026 · Private source

A remote-conducting system that connects a conductor in a Meta Quest headset with musicians in a browser-based virtual rehearsal hall. It spans four repositories: a Unity VR app, a Unity WebGL musician view, a Node.js streaming bridge and a Fastify signaling server, with WebRTC carrying real-time movement data.

My contributions:

- Built the rehearsal hall shared by the VR and browser apps, including paintings, instruments and lighting.
- Added six selectable avatars, a seating plan that shows taken seats, name labels and head look-at.
- Added playing poses with arm IK, so each musician takes up their instrument while the rehearsal timer runs.
- Added per-musician round-trip time to the conductor's view, so connection quality is visible in the headset.

*Unity, C#, TypeScript, Node.js, Fastify, WebRTC, WebSocket*

### Armanly
**Creator** · Sep 2026 to Oct 2026  
[Try the app](https://armannss.github.io/speak-and-learn/) · [Repository](https://github.com/Armannss/speak-and-learn)

An English learning app built for my speaking class, which turns class material into daily lessons and practice.

- Built 29 short lessons covering 151 expressions, with spaced-repetition flashcards and timed speaking drills.
- Made it work offline after the first visit, with all progress stored on the device.
- Added progress transfer between devices through a private link, with no account or server.

*HTML, CSS, JavaScript, Service Worker*

### Belvia Order Calculator
**Creator** · Nov 2025 to Oct 2026  
[Try the app](https://armannss.github.io/) · [Repository](https://github.com/Armannss/Armannss.github.io)

An internal tool for Belvia Online Shop that works out the final price of a customer order and creates a printable invoice.

- Calculates discounts, shipping by weight and totals in euros, Rial and Toman as the user types.
- Supports Persian and English with matching RTL and LTR layouts, Persian digit input, and light and dark themes.
- Keeps the rates and the current order after a refresh, and warns when the saved exchange rate is out of date.

*HTML, CSS, JavaScript, PWA*

### Jetaime
**Creator and developer** · Nov 2026 to present · Private source

Internal tools and a website for a pastry brand, in early development.

- Built a monorepo with an internal tool for cost calculation, price lists and customer invoices, plus a public website.
- Gave the website a restricted database role that can read only published products, so costs and recipes stay out of its reach.

*Next.js, TypeScript, PostgreSQL, Drizzle, Turborepo*

## Education

**B.Sc. in Computer Engineering (in progress)**, Politecnico di Torino, Turin, Italy

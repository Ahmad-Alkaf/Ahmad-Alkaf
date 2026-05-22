# Ahmed Alkaf

**Software Engineer · Makkah, Saudi Arabia**

Three years shipping production systems with TypeScript, React, Next.js, Node.js, tRPC, Prisma, and PostgreSQL. Currently engineering across QA automation, full-stack web platforms, and DevOps at TechTroniX (Jeddah).

My final-year capstone, **ACTS**, was built for the Hadramout Foundation for Autism and won the Gold Medal among 174 international projects at the RIPC Poster Competition in February 2023.

Open to engineering roles in Saudi Arabia and internationally. Reach me at **[Ahmad.Alkaf.ahk@gmail.com](mailto:Ahmad.Alkaf.ahk@gmail.com)** or on **[LinkedIn](https://linkedin.com/in/Ahmad-Alkaf)**.

---

## Selected work

### Production platforms at TechTroniX

**QC Results Web Portal** &nbsp;·&nbsp; `Next.js` `TypeScript` `tRPC` `Prisma` `PostgreSQL` `Shadcn UI` `Docker`
Real-time multi-tenant Next.js dashboard centralizing PC quality-control data, tracking 60+ data points per device across hardware specs, benchmarks, and test results. Bitmask-based access control across 5 roles (admin, QC inspector, support agent, technician, Amazon shipper). Server-Sent Events for live updates, bilingual Arabic-RTL and English-LTR via next-intl, 13 tRPC routers, TanStack Table with URL-synced filtering. Deployed on Hetzner via Coolify with a PostgreSQL service.

**[PC Inspector](https://github.com/Ahmad-Alkaf/PC-Inspector)** &nbsp;·&nbsp; `C#` `.NET` `WinForms`
Desktop QC inspection tool performing 40+ automated hardware checks with one-click auto-fix. Custom script interpreter and macro runner, multi-threaded UI with safe cross-thread synchronization, hardware abstraction layer for CPU / GPU / RAM / storage detection. **Doubled the number of PC assemblers each QC inspector can cover.**

**Automated Stress Testing** &nbsp;·&nbsp; `C#` `WinForms`
Zero-click stress-test runner that triggers automatically at PC startup, eliminating repetitive manual setup. **Doubled the number of PCs that can be stress-tested simultaneously.**

**TTX Automation Suite** &nbsp;·&nbsp; `Puppeteer` `Node.js` `TypeScript` `Electron` `Docker` `Coolify`
Browser-automation platform with an Electron desktop GUI for task management. Automates Amazon FBA order processing and marketplace data collection across Amazon, Noon, and Trendyol. JSON-based task registry with CLI argument parsing, bundled Chromium for standalone deployment, Google Sheets API sync, Amazon SP-API integration. Deployed on Hetzner via Coolify.

**Amazon FBA Shipment Management** &nbsp;·&nbsp; `Next.js` `TypeScript`
Nine-step shipment workflow with barcode-scan verification (FNSKU / UPC / EAN), camera-based mobile scanning, drag-and-drop box packing, automated Amazon Seller Central Excel generation, and PDF label processing with FNSKU / ASIN annotations.

**Product Lookup & Revenue Calculator API** &nbsp;·&nbsp; `Node.js` `Google Apps Script` `Google Sheets API` `Amazon SP-API`
Queue-based microservice for the purchasing team. Accepts EAN / UPC barcodes, performs ASIN lookups via Amazon Seller Central, retrieves current prices and FBA fee breakdowns, and writes calculated net revenue per unit back to spreadsheets.

### Open source

**[ACTS — Autism Children Technical System](https://github.com/Ahgaff-Level4/ACTS)** &nbsp;·&nbsp; `NestJS` `Angular` `MySQL` `Docker`
Final-year university capstone deployed locally at the Hadramout Foundation for Autism charity. Goal-assignment, progress-tracking, and evaluation tooling for trainers, with weekly / monthly / annual reports for parents. Bilingual Arabic and English, vertical activity timeline tailored to each role, database backup / restore. **Won Gold Medal among 174 international projects at the RIPC Poster Competition (Feb 2023).**

**[Laptop POS](https://github.com/laravel-aaa/Laptop-POS)** &nbsp;·&nbsp; `Laravel` `React` `TypeScript` `MySQL` `AWS` `Paddle`
Cloud point-of-sale platform with subscription billing (Paddle), three paid tiers plus a free tier, multi-role accounts (Cashier / Maintainer / Owner), and responsive UI. AWS infrastructure: S3, EC2, RDS, CodePipeline. Live at **[Laptop-POS.com](https://Laptop-POS.com)**.

**[Schedule Builder](https://github.com/Ahmad-Alkaf/Schedule-Builder)** &nbsp;·&nbsp; `Angular` `ASP.NET` `C#` `MSSQL`
Lecture-schedule construction web app with backtracking-algorithm auto-generation, drag-and-drop manual editing, real-time collision detection with red-flash visual cues, and HCI-focused keyboard shortcuts. Live at **[Schedule-Builder.alkaf.org](https://Schedule-Builder.alkaf.org)**.

**[FileUtility](https://github.com/Ahmad-Alkaf/FileUtility)** &nbsp;·&nbsp; `C#` `.NET`
File-and-directory manipulation library for .NET Framework with native async / await support and automatic retries for transient failures (network drives, cloud-mounted storage).

### Side projects

**Certificate Management Platform** &nbsp;·&nbsp; `TanStack Start` `TypeScript` `Better Auth` `Prisma` `PostgreSQL` `Playwright` `Vitest` `Docker`
Multi-tenant SaaS for organizations to issue training certificates with JSON-configured templates and QR-code verification. Organization-isolated data for courses, participants, trainers, and certificates. Bilingual Arabic / English with RTL via Paraglide JS. Test coverage with Playwright (end-to-end) and Vitest (unit).

**[QRForge](https://github.com/Ahmad-Alkaf/qr-generator)** &nbsp;·&nbsp; `Next.js` `TypeScript` `Clerk` `Prisma` `PostgreSQL`
QR-code generator with two modes: Direct (content encoded straight into the QR) and Tracked (short-URL redirect with scan analytics covering geo and user agent, plus editable destinations). Eight QR types (URL, Wi-Fi, vCard, Email, SMS, WhatsApp, PDF, plain text). Three download formats (PNG, SVG, PDF) generated client-side.

**SetupForge** &nbsp;·&nbsp; `Next.js` `TanStack Virtual` `.NET WinForms` `WinGet` `PowerShell`
Pick Windows apps from the WinGet catalog on a web frontend; the server generates a custom .NET WinForms installer EXE that installs all selected apps unattended. Server-side TanStack Virtual grid with chunked search filtering. Companion installer ([**TouchlessSetup**](https://github.com/Ahmad-Alkaf/TouchlessSetup-winforms)) ships a JSON-driven action interpreter with parallel / sequential execution and PowerShell integration.

**[ImageForge](https://github.com/Ahmad-Alkaf/image-utility)** &nbsp;·&nbsp; `Next.js` `TypeScript` `Sharp` `AWS S3` `Clerk`
Image-processing utility with AI background removal, server-side processing via Sharp (resize, format conversion, optimization), client-side compression, EXIF metadata extraction, and batch downloads via JSZip. Storage on AWS S3, authentication via Clerk.

---

## Tech

| Area | Stack |
|---|---|
| **Languages** | TypeScript, JavaScript, C#, SQL, PHP |
| **Frontend** | React, Next.js, Tailwind CSS, Shadcn UI, TanStack (Router, Query, Table, Form, Start, Virtual), Angular |
| **Backend** | Node.js, tRPC, Prisma, PostgreSQL, NestJS, Express, Laravel, ASP.NET |
| **Desktop & native** | C#, .NET, WinForms, Electron |
| **QA & testing** | Playwright, Vitest, React Testing Library, Puppeteer |
| **DevOps & infra** | Docker, GitHub Actions, Coolify, Hetzner Cloud, AWS (S3, EC2, RDS, CodePipeline) |
| **Auth & integrations** | Better Auth, Clerk, Google Sheets API, Amazon SP-API |

---

## Education

**B.Sc. Computer Information Systems** &nbsp;·&nbsp; Al-Ahgaff University &nbsp;·&nbsp; 2019 – 2023
GPA 4.12 / 5. Excellence Certificate for the second-highest GPA among peers.

## Credentials

- **Saudi Engineers Association** — registered member, Allied Engineering Specialist
- **AI ERA NEON Bootcamp — Artificial Intelligence Path** (Neon × IBM SkillsBuild), 2026
- **Claude 101**, **Claude Code 101**, **Claude Code in Action** — Anthropic Academy, 2026

## Languages

- **Arabic** — native
- **English** — fluent

---

## Get in touch

Currently exploring engineering opportunities. The fastest reply is by email at **[Ahmad.Alkaf.ahk@gmail.com](mailto:Ahmad.Alkaf.ahk@gmail.com)** or via **[LinkedIn](https://linkedin.com/in/Ahmad-Alkaf)**. Open to relocation across Saudi Arabia and internationally.

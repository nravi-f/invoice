# Invoice

Enterprise Invoicing Management System — a responsive, client-side public demo built with React, TypeScript, and Vite.

## Demo mode

All records are fictional and intended for interface demonstration only. Records created or changed in a session are held in browser memory and reset on reload; the selected color theme is saved in local storage. There is no backend, real authentication, payment processing, or real customer data. Do not enter sensitive information.

## Run locally

1. Install Node.js 20 or newer.
2. Run `npm install` (or `pnpm install`).
3. Run `npm run dev` (or `pnpm dev`) and open the local URL shown in the terminal.
4. Run `npm run build` (or `pnpm build`) to create the production build in `dist/`.

## GitHub

Create a repository named `invoice` in your GitHub account. In this folder, run `git init`, `git add .`, `git commit -m "Initial invoice demo"`, then add your repository as `origin` and push the `main` branch. Review files before making the repository public.

## Vercel

Import the GitHub repository in Vercel. Use build command `npm run build`, output directory `dist`, install command `npm install`. No environment variables are required. `vercel.json` supports client-side route refreshes.

## Features

Dashboard, customers, products & services, quotations, sales orders, invoices, payments, expenses, approvals, reports, user management, audit logs, and settings. Light/dark themes, responsive navigation, searchable/filterable tables, record creation, status actions, notifications, export, and persistent demo preferences.

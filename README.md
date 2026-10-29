# InvoiceFlow

InvoiceFlow is a local-first freelance and agency management dashboard built with React, Vite, and LocalStorage. It helps track clients, projects, invoices, partial payments, time entries, expenses, and estimated project profitability.

## Run locally

1. Install Node.js (LTS).
2. Open this folder in VS Code.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Features

- White and warm-yellow visual theme
- Revenue overview and project budget-vs-invoiced charts
- Client and project management, including project archive/restore
- Invoice creation, partial payments, status tracking, and print/PDF workflow
- Time tracking, expenses, and estimated profitability comparisons
- CSV reporting and JSON backup/restore
- LocalStorage persistence; no backend or database required

## Data notes

Data is stored in the current browser's LocalStorage and does not sync between devices. Export a JSON backup regularly. Clearing browser site data may remove saved records. This demo is not an accounting or tax system; verify financial calculations before using it for real business records.

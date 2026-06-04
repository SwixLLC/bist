# Badrane International School — Tanger

Official website and administration panel for **Badrane International School**, Tanger, Morocco.

## Structure

```
bist/
├── src/       # School website (React + Vite)
└── admin/     # Admin dashboard (React + Vite)
```

## Stack

- **Frontend** — React, Vite, Tailwind CSS
- **Backend** — Supabase (database, auth, storage)
- **Languages** — French & Arabic (RTL support)

## Getting Started

Install dependencies and start each app:

```bash
# School website
npm install
npm run dev

# Admin panel
cd admin
npm install
npm run dev
```

Both apps require a `.env` file with the Supabase project credentials:

```
VITE_SUPABASE_URL=...
VITE_SUPABASE_ANON_KEY=...
```

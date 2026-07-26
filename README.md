# GDGoC HANU - GPlatform CMS 3.0

Powered by **Nuxt 4**, **Nuxt UI**, and **Supabase**, using **Bun** as the package manager and runtime.

[![Nuxt UI](https://img.shields.io/badge/Made%20with-Nuxt%20UI-00DC82?logo=nuxt&labelColor=020420)](https://ui.nuxt.com)
[![Bun](https://img.shields.io/badge/Package%20Manager-Bun-fbf0df?logo=bun&logoColor=black)](https://bun.sh)

---

## ⚡ Tech Stack

- **Framework**: [Nuxt 4](https://nuxt.com)
- **UI System**: [Nuxt UI v4](https://ui.nuxt.com)
- **Database & Auth**: [Supabase](https://supabase.com) (`@nuxtjs/supabase`)
- **Package Manager**: [Bun](https://bun.sh)

---

## 🚀 Setup & Installation

Make sure you have [Bun](https://bun.sh) installed.

```bash
# Install dependencies
bun install
```

---

## 🛠️ Development

Start the local development server on `http://localhost:3000`:

```bash
bun run dev
```

---

## 📦 Production & Scripts

```bash
# Build for production
bun run build

# Preview production build locally
bun run preview

# Run ESLint
bun run lint

# Run Nuxt Typecheck
bun run typecheck
```

---

## 🗄️ Supabase Type Generation

Generate TypeScript types from your Supabase project:

```bash
# Generate types from remote project (update project-id in package.json or command)
bun run typegen

# Or generate from local Supabase instance
bunx supabase gen types typescript --local > app/types/database.types.ts
```

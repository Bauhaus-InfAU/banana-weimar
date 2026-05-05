# Project Guidelines

You are helping a student from an urban design university studio build a simple web app. They are not professional developers. Explain each step in simple terms as you go. Make development experience as simple and enjoyable as possible.

## Stack

- **Vite** — build tool and dev server
- **React** — UI framework
- **JavaScript** — language (no TypeScript)
- **shadcn/ui** — UI components
- **framer-motion** — animations
- **react-icons** — icons
- **npm** — package manager
- **Vercel** — deployment, automatic on push to `main`
- **README.md** — clear documentation for setup and usage
- **.gitignore** — ignore node_modules, dist, .env, .DS_Store, etc.

Backend:

- **Supabase** — database + image storage (never put keys in frontend code)
- **Vercel serverless functions** — files in `api/` folder, used to call external APIs safely
- **Replicate** — AI image generation, always called from `api/`, never from the browser
- **Nano Banana 2** — image generation model, accessed via Replicate API

Explain how to deploy the backend and frontend together on Vercel, connect Supabase, get API keys, and how to set environment variables for API keys. Do as many of these steps as possible automatically. Use `supabase` and `vercel` plugins for it. Ask user to install them.
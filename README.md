# Varatharajan V — Portfolio

Responsive portfolio website for Varatharajan V, Senior Full Stack .NET Engineer.

## Requirements

- Node.js 22.13 or newer
- pnpm 11

## Run locally

```bash
corepack enable
corepack prepare pnpm@11.25.0 --activate
pnpm install
pnpm dev
```

Open `http://localhost:5173` in the browser.

## Production build

```bash
pnpm build
pnpm start
```

Use the local address printed in the terminal after `pnpm start`.

## Add to a GitHub repository

1. Extract this ZIP.
2. Create an empty GitHub repository.
3. Run these commands from the extracted project folder:

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

Replace `USERNAME` and `REPOSITORY` with the correct GitHub details.

## Important hosting note

This project uses Vinext with server-side routing. It can be stored and developed from GitHub, but it is not a direct static GitHub Pages project. Deploy it through a compatible Node.js or Cloudflare Workers hosting service.

## Main project files

- `app/page.tsx` — home page
- `app/globals.css` — responsive styling and animations
- `app/projects/` — project detail routes
- `components/` — navigation, motion and reusable components
- `lib/projects.ts` — project content
- `public/` — avatar, project images, technology icons and résumé

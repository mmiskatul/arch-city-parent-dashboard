# Parent Dashboard (Standalone)

This folder is a standalone Next.js app containing only the Parent Dashboard module.

## Run locally

1. `npm install`
2. `npm run dev`
3. Open `http://localhost:3000/parent-dashboard`

## Docker

1. Build image: `docker build -t parent-dashboard .`
2. Run container: `docker run -p 3000:3000 parent-dashboard`
3. Open `http://localhost:3000/parent-dashboard`

## Deploy to Vercel

1. Push this folder to a Git repository.
2. Import the repository in Vercel.
3. Framework preset: `Next.js` (auto-detected by `vercel.json`).
4. Build command: `npm run build`.
5. Output setting: default for Next.js.
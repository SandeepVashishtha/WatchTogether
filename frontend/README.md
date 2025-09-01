## Frontend (React + Vite)

This is the React frontend for WatchTogether — a YouTube watch party app with real‑time video/audio chat.

### Prerequisites
- Node.js 20.11.1 (supported via pinned Vite 4.x)
- npm 10+

### Run locally (Windows PowerShell)
```powershell
cd frontend
npm install
npm run dev
```

Open the printed URL (e.g., http://localhost:5173) in your browser.

### Notes
- We pin `vite@^4.4.9` and `@vitejs/plugin-react@^4.0.0` to support Node 20.11.1.
- If you upgrade Node to ≥ 20.19 or 22.12, you can bump Vite to the latest.

### Scripts
- `npm run dev` – start dev server
- `npm run build` – production build
- `npm run preview` – preview build locally
- `npm run lint` – run ESLint

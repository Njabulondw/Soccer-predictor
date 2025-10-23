# soccer-predictor

Ready-to-deploy Vite + React app for the Soccer Predictor.

## Local dev

```bash
npm install
npm run dev
# open http://localhost:5173
```

## Build

```bash
npm run build
npm run preview
```

## Docker (optional)

```bash
docker build -t soccer-predictor .
docker run -p 8080:80 soccer-predictor
# open http://localhost:8080
```

## Deploy on Vercel (Docker mode)

1. Push this repo to GitHub.
2. On Vercel, import the repo. Vercel will detect the Dockerfile and use it.

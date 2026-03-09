# 🎬 Reel Maker

Zero-dependency static app. No build step.

## Structure
```
reel-maker/
├── public/
│   └── index.html   ← entire app
├── vercel.json
├── .gitignore
└── README.md
```

## Deploy

### Vercel (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new) → import the repo
3. **Framework Preset: Other** — leave all other settings default
4. Click Deploy ✅

### GitHub Pages
1. Push to GitHub
2. Settings → Pages → Source: **main branch / `public` folder**
3. Save — live at `https://<you>.github.io/<repo>`

## AI Captions
Calls the Anthropic API directly from the browser. On first use, a banner
prompts for your `sk-ant-...` key. It lives in memory only — never persisted.

Get a key: [console.anthropic.com](https://console.anthropic.com)

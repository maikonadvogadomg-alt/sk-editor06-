# SK Editor v3 — Netlify

## Deploy

1. Arraste o ZIP no Netlify ou conecte o repositório
2. Build command: `pnpm install && pnpm build`
3. Publish dir: `dist`
4. Configure nas Environment Variables: `GEMINI_API_KEY` (opcional)

## Endpoints de API (Netlify Functions)

- `/api/ai/chat`    — IA gratuita (Gemini)
- `/api/ai/forward` — Proxy com auto-detecção de chave

Gerado em: 06/07/2026, 20:36:17

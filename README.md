# nextjs-chat

[![CI](https://github.com/m4rv4x/nextjs-chat/actions/workflows/ci.yml/badge.svg)](https://github.com/m4rv4x/nextjs-chat/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/m4rv4x/nextjs-chat)

> An open-source AI chatbot built with Next.js, the Vercel AI SDK, OpenAI, and Vercel KV.

![Demo](docs/demo.gif)

## ✨ Features

- 🧠 **OpenAI** chat via Vercel AI SDK — streaming responses
- 💾 **Vercel KV** — persisted chats per user
- 🔐 **NextAuth** — email + OAuth login
- 🎨 **Tailwind + shadcn/ui** — polished UI
- ⚡ **Next.js 14** App Router, Server Components, Server Actions

## 🚀 Quick Start

### 1. Clone & install

```bash
git clone https://github.com/m4rv4x/nextjs-chat.git
cd nextjs-chat
pnpm install
```

### 2. Configure

```bash
cp .env.example .env
```

Fill `.env` with:

| Variable | Where to get it |
|----------|----------------|
| `OPENAI_API_KEY` | https://platform.openai.com/account/api-keys |
| `AUTH_SECRET` | `openssl rand -base64 32` |
| `KV_URL` / `KV_REST_API_*` | https://vercel.com/docs/storage/vercel-kv/quickstart |

### 3. Run

```bash
pnpm dev
```

Open http://localhost:3000

## 🏗️ Deploy

One click to Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/m4rv4x/nextjs-chat)

## 🧪 Scripts

```bash
pnpm dev        # Dev server
pnpm build      # Production build
pnpm start      # Production server
pnpm lint       # ESLint + Prettier check
```

## 📚 Stack

- [Next.js 14](https://nextjs.org/)
- [Vercel AI SDK](https://sdk.vercel.ai/)
- [NextAuth.js](https://next-auth.js.org/)
- [Vercel KV](https://vercel.com/docs/storage/vercel-kv)
- [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/)
- [TypeScript](https://www.typescriptlang.org/)

## 📄 License

[MIT](LICENSE) © [marvax](https://github.com/m4rv4x)

---

Based on the [Vercel AI Chatbot](https://github.com/vercel/ai-chatbot) starter.

<div align="center">
	<h1>VA(general purpose): Fast, Open-Source Voice Assistant</h1>
	<p>
		<b>Author:</b> Subhadeep Paul<br>
		<b>Powered by:</b> Groq, Cartesia, Vercel
	</p>
</div>

---

## 🚀 Overview

<b>VA(general purpose)</b> is a blazing-fast, open-source voice assistant built with Next.js, React, and TypeScript. It leverages on-device Voice Activity Detection (VAD), Groq LLMs, and modern web technologies to deliver a seamless, privacy-friendly conversational experience—right in your browser.

---

## ✨ Features

- 🎤 **Real-time Voice Input**: Uses on-device VAD for instant speech detection and transcription.
- 🤖 **AI-Powered Responses**: Integrates with Groq LLMs for natural, context-aware conversations.
- 🖥️ **Modern UI**: Clean, responsive interface with Tailwind CSS and custom icons.
- 🔒 **Privacy-First**: Audio is processed locally before being sent for transcription.
- ⚡ **Fast & Lightweight**: Optimized for speed and low resource usage.

---

## 🛠️ Tech Stack

- [Next.js 15](https://nextjs.org/)
- [React 19](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Groq SDK](https://github.com/groq/groq-sdk)
- [onnxruntime-web](https://www.npmjs.com/package/onnxruntime-web)
- [@ricky0123/vad-react](https://github.com/ricky0123/vad)
- [Vercel Analytics](https://vercel.com/analytics)

---

## 🚦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ai-ng/VA(general purpose).git
cd VA(general purpose)
```

### 2. Install Dependencies

Using [pnpm](https://pnpm.io/):

```bash
pnpm install
```

Or use `npm install` or `yarn` if you prefer.

### 3. Run the Development Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) to use VA(general purpose) in your browser.

---

## 🧩 Project Structure

```
├── app/
│   ├── api/           # API routes (voice transcription, chat)
│   ├── lib/           # Custom hooks and UI components
│   ├── globals.css    # Global styles (Tailwind)
│   ├── layout.tsx     # App layout
│   └── page.tsx       # Main UI
├── public/            # Static assets
├── package.json       # Project metadata & scripts
├── tailwind.config.ts # Tailwind CSS config
└── ...
```

---

## 🗣️ Usage

1. Click the microphone button to start speaking.
2. Speak your query—VA(general purpose) will detect your voice and transcribe it automatically.
3. Get instant, AI-powered responses in natural language.

---

## 🧪 Scripts

- `pnpm dev` — Start development server
- `pnpm build` — Build for production
- `pnpm start` — Start production server
- `pnpm lint` — Lint codebase

---

## 📦 Deployment

Deploy easily to [Vercel](https://vercel.com/) or your preferred platform. See `vercel.json` for region config.

---

## 🙏 Credits

- **Author:** Subhadeep Paul
- **Core Tech:** Groq, Cartesia, Vercel, Ricky0123 VAD, ONNX, Tailwind CSS

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

# Brah

This is Ziad's fork of [KenKaiii/brah](https://github.com/KenKaiii/brah).

**Brah** is a desktop voice assistant that lives in the corner of your screen. Talk to it and it listens, looks at your screen, and gets things done in realtime through the OpenAI Realtime API.

It's not just a chatbot. It takes screenshots, reasons about what's on screen, automates the browser, and manages tasks and calendar, hands-free.

## What it does

- **Realtime voice** — low-latency voice in/out via the OpenAI Realtime API
- **Sees your screen** — screenshots of any window or display
- **Computer use** — browser mode (Playwright) and OS mode (nut.js)
- **Planner** — tasks and calendar
- **Web search & fetch** — live information on demand

## Getting started


```bash
git clone https://github.com/KenKaiii/brah.git
cd brah
npm install
npm start
```

Sign in to OpenAI from inside the app to start a Realtime session.

## For developers

```bash
npm run check   # format + lint (Biome)
npm test        # check + Node test suite
npm run build:mac
```

Stack: Electron + OpenAI Realtime API + Playwright + nut.js

## License

MIT

---

Built by [Ziad Ahmed](https://github.com/Ziad-NasrEldin) at [MaVoid](https://mavoid.com).

[Website](https://mavoid.com) · [LinkedIn](https://linkedin.com/in/ziad-ahmed-634202332) · [GitHub](https://github.com/Ziad-NasrEldin)

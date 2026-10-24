# ENDRAX AI V6 — demo bundle

This is an original, phone-friendly GitHub Pages demo, not a copy of another JARVIS repository. It preserves the existing face.png and provides moving glow, an approximate mouth animation, microphone amplitude indication, local upload previews, and demonstrative information cards.

## Works now
- Static GitHub Pages site (`index.html` + `face.png` at repository root)
- Face glow and basic mouth motion on microphone sound
- Mic toggle with permission prompt (does **not** understand spoken commands)
- Optional browser text-to-speech talking demo, depending on installed Sinhala voice support
- YouTube search link, weather/news external links, message/link cards, photo/video/PDF local selection

## Not connected yet
- Real AI language-model backend, memory, authentication
- Live search and live cards (YouTube/weather/news)
- AI generated images and videos, PDF/video understanding
- Accurate 3D head movement and phoneme-based lip sync
- Browser speech recognition (Safari support is variable)

## Install on the EXISTING repo
1. In GitHub, switch to `endrax-v6` branch, not `main`.
2. Upload `index.html`, `face.png` and `README.md` to the repository root. Replace only the versions on `endrax-v6`.
3. Commit. Do not upload the ZIP itself to GitHub Pages.
4. GitHub Pages currently points at main: to preview this V6 branch safely, use a separate deploy/test environment or preview the HTML locally. Do not change Pages source from main until V6 has been reviewed.

## Safety
Do not place API secrets in this HTML. A separate protected backend will be needed for real AI. The microphone uses getUserMedia; audio is processed locally within the browser in this demo and is not uploaded.

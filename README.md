# Lexi – Voice Vocabulary Coach

Lexi reads out a word's definition, and you say the word. She checks your spoken answer, gives hints, and brings back the words you missed.

Built with plain HTML, CSS and JavaScript, plus Three.js for the 3D glass orb. No build step, no backend.

## Features

- **Voice in, voice out:** Web Speech API (speech recognition for your answer, speech synthesis for Lexi's questions).
- **Forgiving answer matching:** Levenshtein edit distance tolerates small speech-recognition errors.
- **3D glass orb:** a translucent, iridescent Three.js orb that reacts to Lexi's state: idle, listening, thinking and speaking. Falls back to a CSS orb if WebGL is unavailable.
- **Hints and commands:** say or tap *hint*, *repeat* or *skip*. Missed words are asked again at the end of the session.
- **Six views:** Home, Practice, Word Bank, Progress, Conversation History and Settings.
- **Progress tracking:** accuracy, streaks, words learned and a 7-day chart, saved in your browser (localStorage).
- **Settings:** speech on/off, speaking speed, default level, words per session, reduce motion.
- **Accessible and responsive:** keyboard focus styles, live regions, reduced-motion support, mobile tab bar.
- **Typed fallback:** if the microphone is blocked or unsupported, you can type your answers.

## How to run

Open `index.html` in Chrome, Edge or Safari, allow microphone access, and press **Start Practicing**. It also works on GitHub Pages. The page loads fonts and Three.js from CDNs, so it needs an internet connection for the full look.

## Tech

JavaScript, Web Speech API, Three.js (r149), Levenshtein distance, CSS glassmorphism.

## Author

Reddy Hema Sri Asritha

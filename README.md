# Lexi – Voice Vocabulary Coach

A browser-based voice coach for learning vocabulary. Lexi reads out a word's definition, and you say the word. It checks your spoken answer, gives hints, and brings back the words you missed.

Built with plain HTML, CSS and JavaScript. No frameworks, no backend.

## Features

- **Voice in, voice out:** uses the Web Speech API (speech recognition for your answer, speech synthesis for Lexi's questions).
- **Fuzzy answer matching:** Levenshtein edit distance tolerates small speech-recognition errors, so "ephemral" still counts as "ephemeral".
- **Three levels:** Everyday, Advanced, or Mixed, drawn from a 20-word bank.
- **Hints and commands:** say or tap *hint*, *repeat* or *skip*. The first hint gives the first letter and length; the second gives a fill-in-the-blank sentence.
- **Learning loop:** words you miss or skip are asked again at the end of the session.
- **Progress tracking:** score, streak and progress shown live.
- **Typed fallback:** if the microphone is blocked or unsupported, you can type your answers.

## How to run

Open `index.html` in a browser (Chrome, Edge or Safari work best for voice), allow microphone access, and press **Start session**. It also works when hosted on GitHub Pages.

## Tech

JavaScript, Web Speech API (SpeechRecognition and SpeechSynthesis), Levenshtein distance, HTML/CSS.

## Author

Reddy Hema Sri Asritha

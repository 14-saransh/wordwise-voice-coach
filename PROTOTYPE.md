# Wordwise voice vocabulary prototype

Live: https://wordwise-voice-coach.vercel.app

Open in Chrome or Edge, click Start speaking, and allow microphone access. Practice a word or say explain, example, quiz, or next. In quizzes say one, two, or three. Typed input provides an alternative.

A dependency-free static prototype with 10 curated words, two collections, browser speech synthesis and recognition, rule-based coaching, and session quiz scoring. It does not use an LLM or assess pronunciation quality. Speech recognition can depend on the browser's online speech service. No app server stores voice recordings. Progress resets on reload.

Deploy index.html as a static Vercel project; no build step or environment variables. Source is stored on GitHub; the initial production deployment was uploaded directly through the Vercel connector.

Validation: JavaScript syntax, live page rendering, typed word feedback, quizzes and score updates, next command, collection change, and session completion checked. End-to-end real microphone recognition and audible speech require testing on a user's supported browser; the automated browser did not provide working speech audio.

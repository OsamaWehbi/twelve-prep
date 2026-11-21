# Twelve Prep

A personal practice tool for the CELPIP-General test. It has full mock exams and single-part practice for Listening, Reading, Writing and Speaking. Every question is newly written by AI, and Writing and Speaking are rated by AI.

**Live site:** https://osamawehbi.github.io/twelve-prep/

## How it works
- A single static page (`index.html`). There is no server code.
- The AI runs on the user's own Google Gemini or Claude API key, entered in Settings. Keys are kept in the browser and are never part of this repository.
- Optional Google sign-in (Firebase Auth) syncs progress through Firestore. Access is limited by the security rules (`firestore.rules`) to approved accounts, and each person can reach only their own records.
- The Firebase web config in `index.html` is a public identifier, not a secret. The API key is restricted to this site.

## Disclaimer
Twelve Prep is an independent practice tool. It is not affiliated with, endorsed by or connected to Paragon Testing Enterprises. CELPIP is a trademark of Paragon Testing Enterprises. All practice questions are newly written by AI and are not official test material. Levels shown are practice estimates, not official scores.

# Rust Systems Engineering Learning Lab 🦀

A standalone, zero-dependency lesson tracker for a Rust learning plan that builds toward a tested mecanum-drive library and a Raspberry Pi rover motor/encoder subsystem.

## What it includes

- An eight-module roadmap with **all lesson titles and descriptions**
- Completed/remaining lesson and module counts
- Individual lesson checkmarks, with Lesson 1.1 already marked complete
- A built-in full Lesson 1.2 on primitive data types with code snippets, common mistakes, a coding exercise and a self-check quiz
- An engineering notebook for every lesson
- Light/dark theme, search and filters, mobile-friendly layout
- Local browser autosave, plus JSON export/import backups
- No frameworks, accounts, dependencies, tracking or external requests

**Note:** Only Lessons 1.1 and 1.2 contain complete teaching material at this stage. Remaining lessons are roadmap entries with notes and status controls, intended to be filled in as your learning advances in ChatGPT.

## Run locally

Download `index.html` and double-click it in your file manager. It runs without installation or internet. For reliable browser storage, prefer a consistent website URL through GitHub Pages (see below). Opening it using different origins, browsers or profiles can result in separate local save data.

## Publish on GitHub Pages

1. Use the repository `adarsh8966/learningrsu` (already created). GitHub Pages on a personal free account may require the repository to be public.
2. Keep `index.html`, `README.md`, and `.nojekyll` in the repository root on `main`.
3. In **Settings → Pages**, under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)`, then click **Save**.
4. Once GitHub Pages has deployed, open `https://adarsh8966.github.io/learningrsu/` (substitute your GitHub username and the actual repo name). Deployment can take a few minutes.

If you create the empty repository and give ChatGPT its exact `owner/repo` name, the connected GitHub integration may be used to add or update the app's files directly.

## Data & safety

The dashboard saves progress under the browser's `localStorage` key `rust-systems-lab-v1`. **This does not synchronize across devices**, even when hosted on GitHub Pages. Use **Backups & settings → Export JSON** regularly and import that backup on a new browser or device. Browser data clearing, private/incognito mode, or privacy settings can erase or block the local save.

The dashboard does not run or validate Rust programs. Its quiz only checks multiple-choice understanding, and lesson completion is manually selected after independent coding/review.

## Suggested learning workflow

1. Open the next incomplete lesson.
2. Learn the topic in ChatGPT, then write the exercise yourself in `src/bin/lesson_...rs`.
3. Compile, run, review warnings and errors, and submit the code for feedback.
4. Record lessons learned in your engineering notebook and mark the lesson complete.
5. Export a JSON backup occasionally.

License: Free to use and modify for personal learning.
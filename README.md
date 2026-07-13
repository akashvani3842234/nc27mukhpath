# Flashcards Webapp

A simple, mobile-friendly flashcard web app for memorizing questions and answers. Everything runs in your browser — there are no accounts, no servers, and your flashcard data never leaves your device.

**Open the app:** if this site is hosted on GitHub Pages, the app lives at `nc27_mukhpath.html` (e.g. `https://<username>.github.io/<repo>/nc27_mukhpath.html`). If the file has been renamed to `index.html`, just visit the site's root URL.

> **Tip (iPhone/Android):** open the app in your browser, then use **Add to Home Screen**. It gets its own icon and opens like an app.

---

## Getting started

The app organizes content in three levels: **Folders → Decks → Questions**.

1. Tap **＋ New Folder** and name it (e.g. "Biology").
2. Open the folder and tap **＋ New Deck** (e.g. "Chapter 1").
3. Open the deck and add questions, either by **importing a spreadsheet** or with **＋ Add Question**.

## Importing questions from a spreadsheet

Prepare a spreadsheet with three columns — a header row is optional and detected automatically:

| # | Question | Answer |
|---|----------|--------|
| 1 | What is the capital of France? | Paris is the capital and largest city of France. |
| 2 | What is the powerhouse of the cell? | The mitochondria produces ATP through cellular respiration. |

Then, inside a deck, tap **📥 Import** and either:

- **File** — choose an Excel (`.xlsx`), CSV, or TSV file, or
- **Paste** — copy cells directly from Excel / Google Sheets / Numbers and paste them in.

You'll see a preview of what was found before anything is added. (A `sample-questions.csv` is included in this repository if you want to try it.)

## Managing content

- **Edit a question** — tap it in the deck's question list. You can change the number, question, answer, or the "needs practice" flag, or delete it.
- **Delete several questions** — tap **Select** (top right of the deck), tick the ones to remove, then **Delete**. **Select All** is available too.
- **Delete a deck or folder** — tap the 🗑 icon on its row. Deleting always asks for confirmation first.

## Studying

Open a deck and pick a mode. In every mode you can tap the **question card** (or the big **Flip** button) to flip it, and tap again to hide the answer. Use **‹ ›** to move between cards.

### 👁 Practice
Flip to see the full answer. If you've got it down, tap **Mark as Complete** (tap again to unmark).

### ✏️ Fill In The Blank
Flip to see the **first 4 words** of the answer, with the rest blanked out. Tap the answer card (or the button) to reveal the rest, and tap again to hide it. Mark cards Complete the same way as Practice.

### 🎯 Test
Flip and the answer stays hidden — recall it, then tap **Show answer** to check yourself. Grade yourself with the green ✓ (**Right**) or red ✗ (**Wrong**) button; the app records the result and moves to the next card. Tapping the same grade again clears it.

### ⚠ Needs practice
When a card is marked Complete but you're not fully confident, tap **"Not 100% confident — needs practice"** (shown under the Complete button, and under Right/Wrong in Test mode). Flagged cards get an amber chip in lists.

At the top of each deck's Study section, a filter chooses what you study: **All** or **⚠ Needs practice** — it applies to whichever mode you start next, so you can drill only your weak spots.

## 📊 Summary

- Tap **Summary** on the home screen for an overview of every deck: memorized counts, test results, and needs-practice counts.
- Tap any deck (or **Deck Summary** inside a deck) for the full breakdown: which questions are memorized or not, flagged as needing practice, and answered right or wrong in Test mode. Reset buttons at the bottom clear memorized marks or test results for that deck.

## Backing up and moving between devices

Your data is saved in **your browser's storage on your device**. That means:

- It survives closing the tab or restarting your phone.
- It does **not** sync between devices or browsers, and other people using the same URL **cannot see your data** — everyone gets their own private copy.
- Clearing your browser's website data will erase it — export a backup first.

To back up or move your data, use the **Backup** section on the home screen:

1. **⬆️ Export** — downloads a single `flashcards-backup-YYYY-MM-DD.json` file containing all folders, decks, questions, and progress.
2. Send that file to the other device (AirDrop, email, etc.).
3. **⬇️ Restore** — pick the backup file on the other device. The app shows exactly what will be replaced and asks for confirmation.

## Privacy and security

- The app is a single HTML file with no backend. Your questions and progress are stored only in your browser and are never uploaded anywhere.
- The only network requests are for the reading font and the Excel import library, loaded from public CDNs. The app works offline apart from first-time Excel import (CSV/paste import always works offline).

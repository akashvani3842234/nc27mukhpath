# NC27 Mukhpath — Flashcards App

A mobile-friendly flashcard web app for NC27 Mukhpath preparation, **preloaded with all 50 questions in English, Gujarati, and transliterated Gujarati**.  Open the link and start studying immediately. Everything runs in your browser: no accounts, no sign-in, and your progress is saved privately on your own device.

**Open the app:**  `https://akashvani3842234.github.io/nc27mukhpath/`

> **Tip (iPhone/Android):** open the app in your browser, then use **Add to Home Screen**. It gets its own icon and opens like an app.

---

## What's included

The same content in three languages, organized as three folders:

| Folder | Decks |
|--------|-------|
| **English** | Q & A · Vachanamrut · Swamini Vāto · Satsang Diksha · Prasangs |
| **Gujarati** | Q & A · Vachanamrut · Swamini Vāto · Satsang Diksha · Prasangs |
| **Transliteration** | Q & A · Vachanamrut · Swamini Vāto · Satsang Diksha · Prasangs |

Each folder contains the same 50 questions, but in its respective language. Pick the folder for the language you study in.

## How your progress works

- The questions are built into the page, so **everyone who opens the link starts with the full set**.
- As soon as you start marking cards, your progress (and any edits you make) is saved **in your browser on your device**. Nobody else can see it, and other visitors' marks never affect yours.
- Progress does **not** sync between devices or browsers on its own, but you can export your progress and import it to another device.  See [Backing up](#backing-up-and-moving-between-devices) below to move it.
- Clearing your browser's website data erases your progress **and restores the original 50 questions** — a factory reset, in effect. Export a backup first if you want to keep your marks.

## Studying

Open a folder, then a deck, and pick a mode. In every mode, tap the **question card** (or the **Flip** button) to flip it, and tap again to hide the answer. Use **‹ ›** to move between cards.

### 👁 Practice
Flip to see the full answer. If you've got it down, tap **Mark as Complete** (tap again to unmark).

### ✏️ Fill In The Blank
Flip to see the **first 4 words** of the answer with the rest blanked out. Tap the answer card to reveal the rest; tap again to hide it. Mark cards Complete the same way as Practice.

### 🎯 Test
Flip and the answer stays hidden — recall it, then tap **Show answer** to check yourself. Grade yourself with the green ✓ (**Right**) or red ✗ (**Wrong**) button; the app records the result and moves on. Tapping the same grade again clears it.

### ⚠ Needs practice
Know a card but not 100% confident? Tap **"Not 100% confident — needs practice"** (under the Complete button, or under Right/Wrong in Test mode). Then use the filter at the top of each deck's Study section — **All** vs. **⚠ Needs practice** — to drill only your weak cards in any mode.

## 📊 Summary

- **Summary** (home screen) shows every deck at a glance: memorized counts, test results, and needs-practice counts.
- Tap any deck (or **Deck Summary** inside a deck) for the full breakdown: memorized / not memorized, needs practice, and right / wrong / untested. Reset buttons at the bottom clear memorized marks or test results for that deck.

## Making it your own

You can use the web app to add any other items that you're studying.  You can add these items manually or use the import feature.  Use a CSV file that has 3 columns: **#**, **Question**, and **Answer**.  All changes stay on your device only.

## Backing up and moving between devices

Use the **Backup** section on the home screen:

1. **⬆️ Export** — Downloads a single backup file with all questions and your complete progress.
2. Send the file to your other device (AirDrop, email, cloud storage, etc.).
3. **⬇️ Restore** — Open the app there and pick the backup file. The app shows what will be replaced and asks for confirmation.

## Privacy

The app is a single HTML file with no backend. Your marks, test results, and edits are stored only in your browser and are never uploaded anywhere. The only network requests are for the reading font and the Excel-import library.  Apart from first-time Excel import, the app works offline once loaded.

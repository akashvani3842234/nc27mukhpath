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
- When the app is updated with corrected or new questions, you get them the next time you open it, and your marks stay as they were. Questions you edited yourself keep your version, and anything you deleted stays deleted.
- Progress does **not** sync between devices or browsers on its own, but you can export your progress and import it to another device.  See [Backing up](#backing-up-and-moving-between-devices) below to move it. On iPhone, the Home Screen app and Safari also keep separate progress.
- Clearing your browser's website data erases your progress **and restores the original 50 questions** — a factory reset, in effect. Export a backup first if you want to keep your marks.

## Studying

Open a folder, then a deck, and pick a mode — or tap any question in the deck's list to jump straight into practicing that card. In every mode, tap the **question card** to show the answer, and tap again to hide it. Use **‹ ›** to move between cards; tapping **‹** on the first card loops around to the last card in the deck.

**Choose what to study:** the filter tabs at the top of each deck's Study section — **All**, **Not Memorized**, and **⚠ Needs Practice** (with counts in parentheses) — control which cards are included in whichever mode you start next. Use **Not Memorized** to work on cards you haven't marked Complete yet, or **⚠ Needs Practice** to drill only the cards you've flagged.

### 👁 Practice
Tap the question to see the full answer. If you've got it down, tap **Mark as Complete** (tap again to unmark).

### ✏️ Fill In The Blank
Tap the question to see the **first 4 words** of the answer with the rest blanked out. Tap the answer card to reveal the rest; tap again to hide it. Mark cards Complete the same way as Practice.

### 🎯 Test
Questions come in a **random order** (reshuffled each time you start or tap Start Over). Recall the answer, then tap the question to check yourself. Grade yourself with the green ✓ (**Right**) or red ✗ (**Wrong**) button; the app records the result and moves on. Tapping the same grade again clears it.

### ⚠ Needs Practice
Know a card but not 100% confident? Tap **"Not 100% confident — needs practice"** (under the Complete button, or under Right/Wrong in Test mode). Flagged cards can then be drilled on their own using the **⚠ Needs Practice** filter tab described above.

## 📊 Summary

- **Summary** (home screen) shows every deck at a glance: memorized counts, test results, and needs-practice counts.
- Tap any deck (or **Deck Summary** inside a deck) for the full breakdown: memorized / not memorized, needs practice, and right / wrong / untested. Reset buttons at the bottom clear memorized marks (along with Needs Practice flags) or test results for that deck.

## Making it your own

You can use the web app to add any other items that you're studying.  Open a deck and tap **📝 Edit** (in the Study section) to manage its questions: tap a question there to change or delete it, tap **Select** to delete several at once, or use **＋ Add Question** and **📥 Import** to add more.  For importing, use a CSV file that has 3 columns: **#**, **Question**, and **Answer**.  All changes stay on your device only.

## Backing up and moving between devices

Use the **Backup** section on the home screen:

1. **⬆️ Export** — Downloads a single backup file with all questions and your complete progress.
2. Send the file to your other device (AirDrop, email, cloud storage, etc.).
3. **⬇️ Restore** — Open the app there and pick the backup file. The app shows what will be replaced and asks for confirmation.

## Privacy
The app is a single HTML file with no backend. Your marks, test results, and edits are stored only in your browser and are never uploaded anywhere. The only network requests are for the reading font and, when you open Import, the Excel-import library. Once the page is open, studying works without a connection; opening the app from scratch needs one.

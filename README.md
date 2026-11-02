# Family Trivia Night — JSON question banks (v5)

Upload **all three files** (`index.html`, `grade1.json`, `grade4.json`) to the **same folder** in your GitHub Pages repository. Commit the files and open your published GitHub Pages URL.

- `index.html`: game interface, multiplayer scoring, grade selection, OpenTDB for regular players.
- `grade1.json`: 130 original first-grade questions from the prior version.
- `grade4.json`: 35 original fourth-grade starter questions from the prior version.

The previously supplied fourth-grade reference websites have **not** been copied into this version; this update focuses on moving the existing banks to separate files. New original, fact-checked questions can be appended later.

## Adding a question

Edit the JSON file for the relevant grade. Each entry has this format:

```json
{
  "category": "Science & Nature",
  "question": "Which planet is known as the Red Planet?",
  "answer": "Mars"
}
```

Place a comma between entries, but not after the last one. You can validate JSON with a JSON validator. Duplicate question text is removed automatically at load time.

**Important:** Opening `index.html` directly from your phone's Files app (`file://`) may block reading the JSON files. Use GitHub Pages or a local web server. Regular trivia also needs internet access to fetch OpenTDB questions.

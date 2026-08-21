# Flashcard Decks Hub

A collection of flashcard decks in simple CSV format. No proprietary formats, no lock-in, no app required to contribute — just plain text anyone (and any tool) can read.

## PRs are super welcomed!

Open a pull request — no deck is too niche, too small, or too weird. Seriously, don't hesitate. See [Contributing](#-contributing) below.

##  Format

Each deck is a single CSV file. One card per row, two columns, comma-delimited:

```
What is the derivative of $x^2$?,$2x$
State the formula for kinetic energy.,"$$E_k = \frac{1}{2}mv^2$$"
```

- **Column 1** — the prompt (question/front of card)
- **Column 2** — the explanation (answer/back of card)
- No header row
- Plain UTF-8 text
- **LaTeX formulas are supported** — write them inline using standard `$...$` (inline) or `$$...$$` (block) delimiters, and the viewer will render them
- If your answer contains a comma, wrap that field in quotes: `"$f(x) = x^2, x \geq 0$"`

This format is identical to what **Gemini Notebook** produces when you export generated flashcards — so you can drop a deck straight into this repo with zero conversion.

##  Viewing a deck

You don't need to open the CSV in a spreadsheet to study it. Use the browser-based flashcard viewer available by scanning the QR code printed inside the Flashcard Notebook:

🔗 **https://a.co/d/04drurCr**

Just upload the raw `.csv` file and start flipping through cards immediately — no install, no signup.

## 📁 Repository structure

```
/decks
  /physics
    classical-mechanics.csv
    thermodynamics-formulas.csv
  /math
    calculus-derivatives.csv
  /language
    spanish-verbs.csv
  /history
    world-war-2-dates.csv
  ...
```

Decks are grouped by topic folder. If your topic doesn't have a folder yet, create one.

##  Contributing

1. Fork the repo
2. Add your deck as a `.csv` file under `/decks/<topic>/your-deck-name.csv`
3. Follow the two-column format above (no header row)
4. Open a pull request — that's it!

Guidelines:
- Keep filenames lowercase, hyphen-separated (e.g. `spanish-irregular-verbs.csv`)
- One topic per deck; split large mixed decks if it makes sense
- Fixing typos, correcting answers, or improving existing decks is just as welcome as adding new ones
-The last row of each deck is reserved for metadata and should contain the author’s name, optional contact info, website, or other attribution. If you want, you may also include the license there.

```
"Author: Sevetech https://sites.google.com/view/paperstackpro/home/flashcard-decks","CC BY-NC-SA 4.0"
```


## 📜 License

MIT

---

Found this useful? ⭐ Star the repo and share your own decks — the collection only gets better with more contributors.

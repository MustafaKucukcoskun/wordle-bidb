# Wordle BİDB

**A Turkish Wordle game I built for the ITU IT Department (BİDB).** Guess the five-letter Turkish word in six tries. Each guess colors the letters: green for the right letter in the right place, yellow for a letter that is in the word but elsewhere, gray for a letter that is not in the word.

🇹🇷 İTÜ Bilgi İşlem Daire Başkanlığı için geliştirdiğim Türkçe Wordle oyunu.

## Features

- Three difficulty levels (easy, medium, hard), each with its own word pool.
- Full Turkish keyboard including Ç, Ğ, İ, Ö, Ş and Ü, on screen and on a physical keyboard.
- Words you have already played don't come back.
- Statistics (games played, win rate, current and best streak, guess distribution), stored in `localStorage`.
- Flip, pop and bounce animations, responsive layout for phone and desktop.

## Run it

No build step or server is needed. Open `index.html` in a browser, or serve the folder:

```bash
git clone https://github.com/MustafaKucukcoskun/wordle-bidb.git
cd wordle-bidb
python -m http.server 8080      # http://localhost:8080
```

## Tech

HTML · CSS · JavaScript · jQuery 3.7 · Geist font

## Files

```
index.html    page layout
app.js        game logic, word pools, statistics
style.css     styles and animations
logo.svg, background.jpg
```

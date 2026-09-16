# Elementoro — site text

`content.json` holds every word on [elementoro.vercel.app](https://elementoro.vercel.app).

**Edit the text here and the live site picks it up on the next page load.**
No build, no deploy.

## How to change something

1. Open `content.json` above.
2. Click the pencil (Edit).
3. Find the line you want and change what is inside `"text"`.
4. Click **Commit changes**.
5. Reload the site. Give it a minute — GitHub caches the file briefly.

## The two rules

- **`max` is a word limit.** Paste in more words than that and the extra ones are
  cut, so a long paste can never break the layout. Change the number if a line
  should be allowed to run longer.
- **Only change `text` and `max`.** Leave the key on the left alone — that is how
  the site finds the line.

## If you get it wrong

Nothing breaks. A field left empty, a broken comma, or this file being
unreachable all mean the same thing: the site shows the words it was built with.
At worst an edit does nothing.

Every change is saved in this repo's history, so any edit can be undone.

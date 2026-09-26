# Keywords Play

A single-page keyword cloud builder. Type a center word, add keywords (comma-separated for several at once), and they spiral out around it.

Just open `index.html` in a browser — no install, no build step, no account.

- **Add** — add one keyword, or several separated by commas
- **Tap a word** to remove it
- **Undo** — steps back through any change (add, remove, shuffle, clear, open, center word)
- **Shuffle** — re-arranges the cloud with new colors and rotations
- **Clear** — removes all keywords (Undo brings them back)
- **Save** — downloads the keywords as a `.csv` file that opens in Excel or Notepad
- **Open** — loads a saved `.csv`, or a plain `.txt` list with one keyword per line
- **PNG** — exports the cloud as a 1800×2200 image (preview, then download or long-press to save)
- **Hide** — hides the controls for a clean view

If a keyword doesn't fit, it's listed under the buttons and retried whenever space frees up.
The current cloud is also remembered in the browser between visits.

## Save file format

```
Type,Word,Size,Color,Rotated
Center,Key Points,,,
Keyword,Growth,54,#b4461c,no
Keyword,Revenue,50,#c8900a,no
```

You can edit it in Excel or Notepad. Only `Type` and `Word` are needed — a new row like `Keyword,Teamwork` gets a random size and color when opened.

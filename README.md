# Canola for Catastrophes: project website

ENGN4300 capstone landing page. The whole site is one file: `index.html`.
Any change saved here goes live automatically within a minute or two.

## How to edit (no software needed)

1. Click `index.html` above.
2. Click the pencil icon (top right of the file) to edit.
3. Make your change.
4. Click **Commit changes…** → write a short note (e.g. "Week 9 update") → **Commit changes**.

To find something fast, press `Cmd+F` / `Ctrl+F` inside the editor.

## Weekly updates

Search for `EDIT HERE`. Copy one block like this, paste it at the **top** of the `UPDATES` list, and change the text:

```js
  {
    date: "2026-09-28", tag: "Research",
    title: "Short headline for the week",
    body: ["One or two sentences on what happened."],
    list: [
      "Dot point",
      "Another dot point"
    ],
    next: "What we're doing next week."
  },
```

Keep the commas and quote marks exactly as they are. The newest entry shows open and gets the "Latest" tag automatically.

## Repository and ConOps links

In the same `EDIT HERE` block, paste the links between the quotes:

```js
const LINKS = {
  repository: "https://…",
  conops: "https://…"
};
```

## Photos

1. Upload the photo to this repo (**Add file → Upload files**), e.g. `team-prathvi.jpg`.
2. In `index.html`, search for `Photo`. You'll find placeholder lines like:
   `<div class="ph" role="img" aria-label="Photo placeholder for Prathvi"><span>Photo</span></div>`
3. Replace the `<span>Photo</span>` part with `<img src="team-prathvi.jpg" alt="Prathvi">`.

## If something breaks

Every save is kept. Go to the file → **History**, open the last good version, and copy it back.
Usually it's a missing comma or quote mark in the `UPDATES` list.

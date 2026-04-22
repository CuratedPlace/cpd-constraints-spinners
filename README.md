# Working With Constraints — Spinner Activity

An interactive spinner wheel activity for creative producer training sessions. Facilitators spin 9 configurable constraint wheels across multiple teams and display a live results table.

Built as a single, self-contained HTML file — no installation, no dependencies, no server required.

---

## What it does

- **9 spinner wheels** covering Time, Budget, Location, Team Size, Format, Audience, Resources, Collaborator, and Wild Card
- **Multiple team sessions** — add a new team tab for each group, switch between them, and rename teams at any time
- **Spin All** button to trigger all wheels simultaneously
- **Results table** showing every team's outcomes side by side
- **Configurable** — change spinner titles, entries, brand colours, background colour, and font through an in-app settings panel
- **Click sound** on each spinner tick during a spin
- All configuration is saved automatically in the browser

---

## How to use

### Running the activity

1. Open the live URL in a browser
2. Use **+ New Team** in the session bar to add a team for each group
3. Click a team tab to switch to that team's view
4. Press **Spin** on individual wheels or **Spin All** to spin everything at once
5. Click **Show Results** to open the full results table across all teams
6. Use **↺ Reset** (session bar) to clear the current team's results
7. Use **↺ Reset Session** (header) to wipe all teams and start fresh

### Renaming teams

Click the ✏ icon on any team tab, or double-click the team name. Press **Enter** to confirm or **Escape** to cancel.

### Configuring the activity

Click **⚙ Configure** in the header to open the settings panel. From there you can:

- Change the **font**
- Change the **background colour**
- Edit **brand colours** used across spinner segments
- Edit each spinner's **title** and **entries** (double-click any entry pill to edit it inline)

Changes are saved when you click **Save & Apply**.

---

## Embedding

### Miro

Add an **Embed** widget to your board and paste the GitHub Pages URL. The spinner runs in an iframe — works best as a single facilitated screen rather than multi-user.

### Squarespace

**Option A (recommended):** Add a **Code Block** to your page and paste this, replacing the URL with your own:

```html
<iframe src="https://curatedplace.github.io/cpd-constraints-spinners/spinner-activity.html"
        width="100%" height="900" frameborder="0" style="border:none"></iframe>
```

**Option B:** Paste the contents of the HTML file directly into a Squarespace Code Block (omit the `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` wrapper tags). This runs same-origin so browser storage works fully, but Squarespace's own CSS may affect the layout.

### Any website

Embed as an iframe pointing to the GitHub Pages URL:

```html
<iframe src="https://curatedplace.github.io/cpd-constraints-spinners/spinner-activity.html"
        width="100%" height="900" frameborder="0" style="border:none"></iframe>
```

---

## Browser storage

The app uses `localStorage` to remember your configuration and session data between visits. This works reliably when the page is opened directly. In cross-origin iframes (e.g. embedded in Miro or Squarespace via iframe), some browsers — particularly Safari — may block storage access, meaning settings will not persist after a page refresh.

---

## Multi-user limitations

This is a **single-device tool**. Each browser tab or device gets its own independent instance — teams on separate devices cannot see each other's results. It is designed to be run by one facilitator on a shared screen, with team results entered manually by switching between team tabs.

---

## Updating the activity

To update the file after making changes:

1. Go to your GitHub repository
2. Click `spinner-activity.html`
3. Click the pencil ✏ icon to edit, or use **Add file → Upload files** to replace it
4. Commit the changes — the live URL updates automatically within a minute or two

---

## Credits

Developed by curatedplace.com for [Creative Producer Training](https://www.creativeproducertraining.com).

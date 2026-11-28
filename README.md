# Prime Tuition — Student Projects Gallery

Welcome to the official **Prime Tuition Coding Club** showcase repository. This repository powers our live Student Projects Gallery, where parents, students, and tutors can play interactive games and explore coding projects built in class.

**Live Gallery:** [https://primetuition.github.io/Games/](https://primetuition.github.io/Games/)

---

## About This Showcase

This gallery is hosted using **GitHub Pages** and features student creations built with:
* **MakeCode Arcade** (playable directly in the browser)
* **Scratch** (interactive games and animations)
* **Project Demos & Robotics Videos**

---

## How to Add a New Student Project (For Tutors)

All projects are managed inside `index.html` using a simple list—no build tools or local setup required.

1. Open `index.html` in this repository and click the **Edit (pencil) icon**.
2. Scroll down to the `const projects = [...]` array near the bottom of the file.
3. Add a new entry using the student's MakeCode Arcade Share ID (the code at the end of their Share URL, e.g., `S47326-05730-25883-02581` or `_PE60u94xfePh`):

```javascript
{
  title: "Space Dodger",
  student: "Alex M.",
  term: "Autumn 2026",
  id: "S00000-00000-00000-00000"
},
```

4. Click **Commit changes** directly to the `main` branch.
5. Wait **1–2 minutes** for GitHub Pages to automatically rebuild and publish the updated gallery.

### Notes on Updating Projects
* **Signed-in MakeCode links (`S...`):** If a student updates their game and selects **"Update existing share link"**, the embedded game on the gallery updates automatically.
* **Anonymous MakeCode links (`_...`):** These are fixed snapshots. If the student makes edits and re-shares, replace the old ID in `index.html` with the newly generated ID.

---

## Branding & Logo

The navigation bar displays `logo.png` from the root of this repository. To update the logo, upload a new image named `logo.png` to the root folder (or update the filename in the `<img src="logo.png">` tag inside `index.html`).

---

## Student Privacy Guidelines

Because this repository and GitHub Pages site are **public**, please avoid publishing students' full names or personal details. Use **first names, initials, or project nicknames** (e.g., `Alex M.` or `Team Alpha`) in the `student` field.

---

## Contact

* **Website:** [primetuition.co.uk](https://primetuition.co.uk)
* **Email:** info@primetuition.co.uk
* **Phone:** 0203 302 1524

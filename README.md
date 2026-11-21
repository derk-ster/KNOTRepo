# KNOT

**KNOT** is a collaborative project for tying people together around shared goals. You type in a goal (the demo uses a filmmaking goal), receive explainable complementary teammate matches, and form a group chat. The brand identity centers on a chrome knot rendered in liquid silver with violet reflections — see `Media/KNOT_ALL_ASSETS/` for the full visual asset packs and their `README_FOR_CLAUDE_CODE.md` files for art direction.

## For teammates

### Clone the repository

```bash
git clone https://github.com/<OWNER>/KNOT.git
cd KNOT
```

(Ask the repo owner for the exact URL, or copy it from the repository page on GitHub via the green **Code** button.)

### Open the project in your terminal

```bash
cd path/to/KNOT
```

### Pull the latest changes

Always pull before you start working, and pull again before pushing:

```bash
git pull origin main
```

### Commit and push your changes

```bash
git add .
git commit -m "Describe what you changed"
git push origin main
```

### Avoiding conflicts when working simultaneously

- Pull before you start and before every push (`git pull origin main`).
- Work on separate files where possible — coordinate with each other on who owns which part.
- Make small, frequent commits instead of one large one.
- If `git push` is rejected, run `git pull origin main`, resolve any conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`), then `git add` the resolved files and push again. Never force-push (`--force`) to `main`.
- If you expect a longer-lived change, use a feature branch and open a pull request instead of committing straight to `main`.

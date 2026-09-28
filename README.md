## How to update (Just for me)

When a new version of the career roadmap HTML is generated, replace the existing `index.html` with the new file and push the changes to GitHub.

### 1. Replace `index.html`

For example, if `food_career_roadmap_2026_v11.html` is downloaded:

```bash
cp ~/Downloads/food_career_roadmap_2026_v11.html index.html
```

This copies the new HTML file and overwrites the existing `index.html`.

### 2. Check the changes

```bash
git status
```

Check that `index.html` appears as modified.

### 3. Stage the updated file

```bash
git add index.html
```

### 4. Commit the changes

```bash
git commit -m "Update career roadmap v11"
```

The commit message can be changed as needed.

### 5. Push to GitHub

```bash
git push
```

After the push is complete, GitHub Pages will automatically update the website using the new `index.html`.

---

### Quick reference

```bash
cp ~/Downloads/food_career_roadmap_2026_v11.html index.html
git status
git add index.html
git commit -m "Update career roadmap v11"
git push
```

> **Note:** Run these commands from the local `FnB-roadmap` repository directory.

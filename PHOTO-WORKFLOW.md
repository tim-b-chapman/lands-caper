# Getting your photos into the website
## For someone who has better things to do than organise files

---

### Step 1 — Get photos off your phone (10 mins)

**Easiest option:** AirDrop / USB to your laptop, or just email them to yourself in batches.

Drop them all into a folder called `images` inside the `lands-caper` folder.

Don't stress about renaming yet — just get them off the phone first.

---

### Step 2 — Tag each photo by work type (do this in batches, not all at once)

Rename each photo using this naming pattern:

| Work type | File name format | Example |
|---|---|---|
| Garden design | `garden-design-01.jpg` | `garden-design-01.jpg` |
| Retaining walls | `retaining-wall-01.jpg` | `retaining-wall-02.jpg` |
| Lawn & turf | `lawn-01.jpg` | `lawn-03.jpg` |
| Planting | `planting-01.jpg` | `planting-01.jpg` |
| Paving & paths | `paving-01.jpg` | `paving-02.jpg` |

Just increment the number for each new photo in that category.

---

### Step 3 — Swap a placeholder for a real photo

Open `index.html` in a text editor (Notepad, TextEdit, VS Code — anything works).

Find a placeholder block that looks like this:

```html
<div class="gallery-item" data-category="garden-design">
  <div class="gallery-placeholder">...Add photo: garden-design-01.jpg...</div>
  <div class="gallery-item-overlay"><span class="gallery-item-label">Garden design</span></div>
</div>
```

Replace the whole inner div with an actual image tag:

```html
<div class="gallery-item" data-category="garden-design">
  <img src="images/garden-design-01.jpg" alt="Garden design">
  <div class="gallery-item-overlay"><span class="gallery-item-label">Garden design</span></div>
</div>
```

That's it. Do one at a time. You don't have to do them all at once.

---

### Step 4 — Add more photos to the gallery

Copy and paste this block and fill in the filename and category:

```html
<div class="gallery-item" data-category="CATEGORY-HERE">
  <img src="images/FILENAME-HERE.jpg" alt="Description here">
  <div class="gallery-item-overlay"><span class="gallery-item-label">Label here</span></div>
</div>
```

Categories to use (copy exactly):
- `garden-design`
- `retaining-walls`
- `lawn`
- `planting`
- `paving`

---

### Step 5 — Fill in your real details

Search the file for these placeholders and replace them:

| Find | Replace with |
|---|---|
| `[Your name]` | Your actual name |
| `[X] years` | How long you've been doing this |
| `[X]+` | Rough number of projects done |
| `0400 000 000` | Your phone number |
| `hello@landscaper.com.au` | Your email (appears 3 times) |

---

### Hosting (getting it online)

Simplest free option: **Netlify Drop**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `lands-caper` folder onto the page
3. Done — you get a live URL instantly

Free. No account needed first try. Custom domain can be added later.

---

### If it's all too much right now

Tell Tim. He'll sort it with Claude in one session.

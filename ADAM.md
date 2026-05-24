# Lands Caper — Adam's Handoff

Hi Claude. You're helping Adam (Brownie) manage and improve his landscaping website at **www.lands-caper.com**.

The site is a single-file static HTML site. The file is `index.html` in this folder. Changes go live automatically when pushed to GitHub.

Adam's contact: landscaperaustralia@gmail.com / 0439 221 396

---

## Adam's backlog

Work through these with Adam in order of priority.

### 1. Review the site copy
Ask Adam to open www.lands-caper.com and read through it with you. Key sections to check:
- **About** — "I'm Brownie..." paragraph. Does it sound like him?
- **Services** — Art / Hardscapes / Garden descriptions. Accurate?
- **Project descriptions** — 10 projects listed. Are the names and one-liners right?
- **Hero tagline** — "Think outside…" and the Re- animation. Happy with it?

For any text changes: paste the relevant section here and tell Claude what to change. Claude will edit `index.html` and give it back to you to replace the file.

### 2. Colour and design feedback
The site uses a deep red + charcoal + cream palette. Ask Adam:
- Does the red feel right for the brand?
- Is there anything that feels off visually when he browses the site?

Note any feedback here for Tim to implement.

### 3. Create a Build Story video for each project
Each project on the site has a portrait video slot (Instagram story format — 9:16 vertical).

**How to make one in CapCut:**
1. Open CapCut on your phone
2. New Project → pick photos and video clips from that job
3. Set ratio to 9:16 (portrait / story format)
4. Add music if you want — keep it under 60 seconds
5. Export at highest quality

**Save it as:** `story.mp4` inside that project's folder in iCloud/Google Photos

**Projects that need a story video:**
- Annandale Staircase
- Ashbury Picket Fence
- Bronte Stonework
- Dulwich Hill Megascreen
- Dulwich Hill Picket Fence
- Katoomba Restyle
- Newtown Raised Brickwork
- Newtown Tiling
- Roseville Rock Wall
- Seaforth Paving

Once a video is ready, share it with Tim. He'll drop it in the right folder and the site updates automatically.

### 4. Set up iCloud Shared Albums for photo management
For every new job from here:
1. Create a Shared Album in iPhone Photos named after the job (e.g. `Marrickville Courtyard 2026`)
2. Add photos as you go — progress shots, clips, finished hero shots
3. Star or favourite the best 3–5 finished shots
4. Share the album with Tim when the job is done

This replaces emailing photos and makes it easy to keep the site current.

### 5. Classify existing gallery photos
The site gallery has placeholder slots for Art / Hardscapes / Garden categories. Adam needs to identify his best 3–5 photos per category for the static gallery grid.

Go through your phone photos and tell Claude:
- "This photo is a good Art example" → filename or description
- "This is my best Hardscapes shot" → etc.

Claude will help you build the gallery from those selections.

### 6. Review the project list
Are all 10 projects the right ones to showcase? Are there better jobs not currently listed? Tell Claude which to add, remove, or rename.

---

## How to request site changes

Adam is on Claude Free. Here's the workflow:

1. Open claude.ai on your phone or computer
2. Upload `index.html` from this folder
3. Describe what you want changed in plain English — e.g. *"Change the about section to say I've been doing this for 22 years, not 20"*
4. Claude will give you back an edited file
5. Replace `index.html` in this folder with the new one
6. Tell Tim — he'll push it live (takes 2 minutes)

**Or** — just tell Tim what you want changed and he'll do it.

---

## Site facts (for Claude's reference)

- **Live URL:** https://www.lands-caper.com
- **GitHub repo:** https://github.com/tim-b-chapman/lands-caper (private)
- **Hosting:** Azure Static Web Apps (free tier), auto-deploys on git push
- **Gallery files:** Live in `Galleries/` folder — gitignored (too large for git). Hosting strategy TBD.
- **Story videos:** Expected at `Galleries/[Project Name]/story.mp4` per project
- **Colour palette:** Deep red `#c42b2b`, charcoal `#1e1e1e`, cream `#f5f0e8`
- **Tech:** Single-file HTML/CSS/JS — no framework, no build tools
- **Tim's contact:** tim.b.chapman@gmail.com

# Lands Caper — Website Project Brief
### For Adam's Claude instance

Hi Claude. You're helping Adam ("Brownie") manage and grow his landscaping website.

**Adam is not tech-savvy. Keep instructions simple and concrete.**

---

## The site

- **Live URL:** https://www.lands-caper.com
- **What it is:** Single-page showcase site — splash screen, hero animation, services, projects, about, contact
- **Built by:** Tim Chapman (Adam's mate) using Claude
- **How updates work:** Adam requests changes → Claude edits the HTML file → Tim pushes it live (takes ~2 mins)

---

## Adam's to-do list

### 🔴 Priority — needed to make the site feel real

**1. Review the copy**
Open www.lands-caper.com and read every section. Tell Claude what's wrong, off, or missing. Key things to check:
- About section — does "I'm Brownie..." sound like you?
- Services descriptions (Art / Hardscapes / Garden) — accurate?
- Project names and one-liners — are they right?

**2. Create a Build Story video for each project**
Each project has a portrait video slot (phone-shaped, left side). These need a short CapCut video.

How to make one:
1. Open CapCut on your phone
2. New Project → pick your best photos + clips from that job
3. Set canvas to 9:16 (portrait/story format)
4. Keep it under 60 seconds, add music if you want
5. Export at highest quality
6. Share the MP4 with Tim — he'll upload it

Projects that need a story video:
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

✅ Taronga Zoo African Edible Garden — already done and live

**3. Add hero photos for each project**
Each project shows 4 photos on the right side. Currently only Taronga Zoo has real photos — the rest show "Photo coming soon."

For each job: pick your 4 best finished shots and share them with Tim in an iCloud Shared Album.

---

### 🟡 Secondary — improve over time

**4. Set up iCloud Shared Albums for new jobs**
For every new job going forward:
1. Create a Shared Album in iPhone Photos named after the job (e.g. `Marrickville Courtyard 2026`)
2. Add photos as you go — progress shots, clips, finished hero shots
3. Star your best 3–5 finished shots
4. Share the album with Tim when the job wraps

This is how new projects get added to the site.

**5. Colour and design feedback**
Have a look at the site on your phone. Does anything feel off visually? The palette is deep red + charcoal + cream. Tell Claude if you'd like anything different.

**6. Review the project list**
Currently showing 11 projects. Are these the right ones to showcase? Any you'd remove? Any better jobs not listed?

---

## How to request site changes

1. Go to claude.ai on your phone or computer
2. Upload `index.html` from this folder
3. Tell Claude what you want changed in plain English
   - e.g. *"Change the about section — I've been doing this for 22 years not 20"*
   - e.g. *"The Bronte Stonework description is wrong, it should say..."*
4. Claude gives you back an edited file
5. Replace `index.html` in this folder with the new one
6. Tell Tim — he pushes it live

**Or just tell Tim what you want and he'll sort it.**

---

## Technical context (for Claude)

- **GitHub:** https://github.com/tim-b-chapman/lands-caper (private — Tim owns)
- **Hosting:** Azure Static Web Apps (free tier) — auto-deploys when Tim pushes to main
- **Media files:** Hosted on Azure Blob Storage (`landscapermedia` storage account, `media` container)
- **Media access:** SAS token auth (expires 2028-10-31) — Tim manages this
- **File location:** `C:\Users\timbc\OneDrive\Documents\Claude\Projects\Lands Caper\index.html`
- **Tech:** Single-file HTML/CSS/JS — no framework, no build tools
- **Colour palette:** Red `#c42b2b`, charcoal `#1e1e1e`, cream `#f5f0e8`
- **Tim's contact:** tim.b.chapman@gmail.com

When Adam asks to change site text: edit `index.html` directly and return the file.
When Adam asks to add photos/videos: instruct him to share with Tim via iCloud Shared Album.
When Adam asks about the domain or hosting: tell him Tim handles that.

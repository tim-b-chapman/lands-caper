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

### Step 1 — Review the site
Open www.lands-caper.com and go through it with Claude.

- Read every section — does it sound right? Does it sound like you?
- Check: About, Services (Art / Hardscapes / Garden), each project name and description
- Note anything wrong, missing, or that you'd change
- Give feedback on the look and feel — colours, layout, anything that feels off

Claude will edit the text and return an updated file for Tim to push live.

### Step 2 — Sort out photo and video hosting
Tim will set this up with you. The goal:

- Establish an iCloud Shared Album workflow — one album per job
- Pick your best 4 finished photos per project (hero shots for the site)
- Create a short CapCut video for each project (portrait format, under 60 secs)
- Tim uploads everything to the site once it's ready

✅ Taronga Zoo is already live as the working example.

### Step 3 — Establish the ongoing process with Tim
Once Steps 1 and 2 are done, you and Tim agree on:

- How you share new job photos (iCloud Shared Album)
- How you request text changes (upload index.html to Claude, or just tell Tim)
- How often to update the site with new work

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

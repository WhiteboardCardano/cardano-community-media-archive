# Contributing to the Cardano Community Media Archive

Thank you for your interest in contributing!  
This project aims to preserve and share all multimedia, design, and video
production assets created for Cardano community events.

Because this archive contains **large files**, **multiple event sources**, and
**external storage links**, we follow specific contribution rules to maintain
quality, accuracy, and long-term usability.

Please read the guidelines below before submitting contributions.

---

## 📌 Types of Contributions We Accept

You can contribute in many ways:

### ✔ 1. Metadata & Documentation
- Adding missing information about an event
- Improving asset descriptions or naming
- Correcting inaccurate info
- Adding links to external storage mirrors
- Adding previews or thumbnails to `previews/` folders
- Updating GitBook documentation pages

### ✔ 2. New Event Media Sets
If you have permission to share materials from:
- Cardano Summit events  
- Constitutional events  
- Community gatherings  
- Presentations  
- Workshops or side-events  

You may submit:
- Links to large-file storage (Archive.org, MEGA, IPFS, etc.)
- Metadata files
- Preview images
- Folder structures
- Event summaries

### ✔ 3. Quality Improvements
- Reorganizing inconsistent folders  
- Standardizing naming conventions  
- Adding missing credits  
- Adding missing license information  
- Adding mirrored download links  

### ✔ 4. Bug Reports & Issues
You may report:
- Broken links  
- Missing files  
- Metadata errors  
- Incorrect event labeling  
- Problems in GitBook documentation  

Please open an **Issue** for these.

---

## 📁 Repository Structure Guidelines

The archive uses the following structure:

```
/2022-summit
/2023-summit
/2024-summit
/constitutional-event
/previews
/docs
```

Each event folder may contain:

```
README.md           → Event overview
metadata.json       → Event-level metadata (optional)
index/              → Metadata for each asset pack
previews/           → Small JPEG/PNG preview images
links.md            → External download URLs
credits.md          → Creator & team credits
```

### 📌 Do NOT upload raw multi-GB media directly to GitHub  
Instead:

1. Upload to **Archive.org**, **MEGA**, **IPFS**, **Dropbox**, etc.  
2. Add the links in:
   - `links.md`, **and/or**
   - Event GitBook page  
3. Add preview thumbnails (optional but recommended)

---

## 📝 Naming Conventions

Please follow these conventions:

### File Naming

event-year_category_item-version.format

Examples:

```
2023-summit_stage-graphics_main-v1.psd
2024-summit_motion-pack_01.aep
constitutional-event_social-frame_v2.png
```

### Folder Naming
Use lowercase, hyphen-separated:

```
2022-summit
cardano-constitutional-event
```

---

## 🧾 Metadata Standards (Recommended)

Each event in `/index/` folder should include a Markdown file like:

```
## Opening Keynote Pack
Event: Cardano Summit 2023
Asset Type: Stage Graphics / Motion Graphics / Branding
Contents: PSD, TIFF, AE Projects
Resolution: 4K
Download: Archive.org Link￼
Preview:
License: CC BY-SA 4.0
Credits: Name(s) of designers or teams
```

---

## 🧠 Workflow: How to Contribute

### Step 1 — Fork the repository
Click **Fork** on GitHub.

### Step 2 — Create a new branch
Example:---

```
git checkout -b add-2023-summit-pack1
```

### Step 3 — Add or edit files
You may:

- Add metadata under the correct event folder  
- Add/update preview images  
- Insert external storage links  

### Step 4 — Commit your changes

```
git commit -m “Add metadata and download links for 2023 Summit Pack 1”
```

### Step 5 — Open a Pull Request (PR)
Your PR should include:

- What you added  
- What event it belongs to  
- Any external download links  
- Credits if applicable  

---

## 👥 Credits & Attribution

When adding new materials:

1. Always credit the original designers and creative teams.  
2. Only upload or link files that **you have permission to share**.  
3. Respect the **CC BY-SA 4.0 license** used by this archive.

This helps maintain transparency and honors the creators.

---

## ⚠️ Important Restrictions

Please **do not**:

❌ Upload copyrighted Cardano Foundation / IOG assets that you are *not* authorized to release  
❌ Upload files larger than 100MB directly to GitHub  
❌ Upload raw multi-GB design/video files to the repo  
❌ Remove creator credits  
❌ Change the license of existing materials  
❌ Add non-Cardano-related materials

This protects the integrity of the archive.

---

## 💬 Questions or Support?

If you have questions, feel free to:

- Open an **Issue**
- Start a **Discussion**
- Contact the maintainers (Email listed in README)

Thank you for contributing to the Cardano Community Media Archive!  
Your help preserves the creative history of the ecosystem for years to come.

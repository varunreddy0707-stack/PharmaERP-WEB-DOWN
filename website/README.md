# PharmaERP Download Site

This folder is a standalone static download page for hosting on a free site.

## Quick free setup

1. Create a GitHub repository for the website or use this repo.
2. Create a GitHub Release named `v0.1.1`.
3. Upload these files from [release-builds](</abs/path/c:/Users/user/Desktop/VRB/pharma-erp/release-builds>):
   - `PharmaERP_0.1.1_x64-setup.exe`
   - `PharmaERP_0.1.1_x86-setup.exe`
4. Edit [config.js](/abs/path/c:/Users/user/Desktop/VRB/pharma-erp/website/config.js) and replace:
   - `YOUR_USERNAME`
   - `YOUR_REPO`
   - version if needed later
5. Host the `website` folder on:
   - GitHub Pages
   - Netlify
   - Cloudflare Pages

## Files

- `index.html`: the public download page
- `styles.css`: styling
- `config.js`: download links and release metadata

## Recommended free flow

- Website hosting: GitHub Pages
- Installer file hosting: GitHub Releases

That way:
- your website stays fast
- large EXE files are served by GitHub
- you only update `config.js` for new versions

## Before publishing

- Test both download buttons after upload
- Make sure the 64-bit and 32-bit links point to the correct release assets
- Keep the x64 installer as the main recommended option

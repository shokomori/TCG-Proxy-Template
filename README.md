# Shoko Proxy Maker

Shoko Proxy Maker is a lightweight browser-based tool to create print-ready TCG proxy sheets.

It runs as a single HTML file and works fully on the client side (no backend required).

## Features

- Clean sans-serif UI focused on print workflows
- Multiple proxy size presets:
  - Pokemon / MTG (63 x 88 mm)
  - Credit Card Portrait (53.98 x 85.6 mm)
  - Yu-Gi-Oh! (59 x 86 mm)
  - Cardfight / JP Standard (62 x 89 mm)
  - Mini Euro (44 x 68 mm)
- Image input methods:
  - Click slot and choose file
  - Drag and drop directly onto slot
  - Paste from clipboard (Ctrl+V / Cmd+V)
- Resize behavior options:
  - Fit Width
  - Fit Height
- Multi-page support:
  - Add page
  - Remove page
  - Navigate pages
- PDF export with cut-guide options:
  - Full-page cut lines (edge-to-edge)
  - Card border guides only
  - No guide lines

## Project Structure

- tcg_proxy_maker.html: Main application (UI, logic, export)

## Local Usage

1. Download or clone this repository.
2. Open tcg_proxy_maker.html in your browser.
3. Choose a proxy type and add card images.
4. Export a print-ready PDF.

## Deploy on GitHub

This is a static project, so GitHub Pages is the easiest deployment option.

### 1. Push to GitHub

Run these commands from the project folder:

```bash
git init
git add .
git commit -m "Initial commit: Shoko Proxy Maker"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to your repository on GitHub.
2. Open Settings > Pages.
3. Under Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
4. Save.

### 3. Open Your Live Site

After GitHub finishes deployment, your site will be available at:

https://<your-username>.github.io/<your-repo>/

## Notes

- Keep images and usage legal according to your card game rules and local laws.
- Print on quality paper and use a ruler/craft knife for cleaner cuts.

## License

Choose a license before public release (for example: MIT).

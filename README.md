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

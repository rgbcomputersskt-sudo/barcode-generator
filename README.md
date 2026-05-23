# Barcode Generator

Try the live barcode generator here:  
https://www.creativesoft.shop/barcode-generator


<p align="center">
  <img src="assets/images/logo.svg" alt="Creative Vision IT logo" width="320">
</p>

A modern browser-based barcode generator built with HTML, CSS, JavaScript, Bootstrap, and JsBarcode.

## Features

- Generate barcodes directly in the browser.
- Support for multiple barcode types:
  - Code 128
  - Code 39
  - Code 93
  - EAN-13
  - EAN-8
  - UPC-A
  - ITF
  - ITF-14
  - MSI
  - MSI-10
  - MSI-11
  - MSI-1010
- Live preview with instant updates.
- Custom controls for color, size, margin, and text visibility.
- Download the result as SVG or PNG.
- Responsive Bootstrap-based layout.

## Requirements

- A modern web browser.
- Internet access for the CDN-hosted Bootstrap, Google Fonts, and JsBarcode assets.
- XAMPP or any local web server if you want to run it locally.

## How to Use

1. Open `index.html` in a browser or place the folder inside your web server directory.
2. Type the barcode value in the input field.
3. Select the barcode type that fits your data.
4. Adjust the appearance settings if needed.
5. Click **Generate barcode** or just keep typing for the live preview.
6. Use **Download SVG** or **Download PNG** to save the generated barcode.

## Barcode Type Notes

- Code 128 works best for mixed text, numbers, and symbols.
- Code 39 is useful for simple alphanumeric labels.
- Code 93 offers a denser alternative to Code 39.
- EAN-13, EAN-8, and UPC-A are designed for retail barcodes and need numeric input.
- ITF and ITF-14 are useful for logistics and shipping labels.
- MSI variants are commonly used for inventory and warehouse workflows.

## Project Structure

```text
barcode-generator/
├── index.html
├── README.md
└── assets/
  ├── images/
  │   └── logo.svg
    ├── css/
    │   └── style.css
    └── js/
        └── app.js
```

## Publishing to GitHub

1. Create a new repository on GitHub.
2. Push this folder to the repository.
3. Make sure `index.html` is in the project root.
4. If you want to host it with GitHub Pages, choose the root branch and root folder.

## Customization

- Edit `index.html` to change the branding or copy.
- Edit `assets/css/style.css` to update the visual theme.
- Edit `assets/js/app.js` to add more barcode rules or presets.
- Edit `assets/images/logo.svg` if you want to swap the repo logo.

## Credits

Created By: Creative Vision IT

Website: https://www.creativesoft.shop
## Custom Development

Need a custom business tool, calculator, ERP, CRM, dashboard, or automation system?

We build custom web tools, business software, ERP/CRM systems, automation workflows, and industry-specific calculators.

## Notes

- This project does not require PHP because it runs entirely in the browser.
- If you want to use it offline, download the external CDN assets and update the script and style links.


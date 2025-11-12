# Academic Resume LaTeX Template

A clean, professional LaTeX template for academic resumes featuring QR codes, SVG graphics, and print-friendly formatting.

## Features

- 📄 Clean and professional academic resume layout
- 🎨 Customizable colors and styling
- 📱 QR code integration for contact information
- 🖼️ SVG graphics support
- 🖨️ Print-friendly design
- ⚡ Easy to customize and maintain

## Preview

<p align="center">
  <img src="imgs/cv.png" alt="Academic Resume Preview" width="600" />
</p>

## Quick Start

1. Clone this repository
2. Edit `resume.tex` with your personal information
3. Compile with LaTeX to generate your PDF resume

## Customization Guide

### Changing Colors

Edit the color definitions in your LaTeX file:
```latex
\definecolor{linkblue}{RGB}{111, 153, 222}
```

### Adding Icons

1. Download SVG icons from [FreeIcons.io](https://freeicons.io)
2. Customize icon colors by editing the SVG file:
   - Open the SVG file in a text editor
   - Find the path tag: `<path d="M228.065,125.587l-51...`
   - Add your custom color: `<path style="fill:#AB7C94;" d="M228.065,125.587l-51...`
3. Convert SVG files to PDF using [CloudConvert](https://cloudconvert.com/svg-to-pdf)

### Adding QR Codes

Generate QR codes for contact information using [The QR Code Generator](https://www.the-qrcode-generator.com/) and follow the same SVG customization process above.

## Acknowledgments

This template is inspired by and references the excellent work from [academic-resume-latex](https://github.com/rancheng/academic-resume-latex) by rancheng.

## License

This code is for non-commercial use. Please see the [LICENSE](LICENSE) file for complete terms and conditions.

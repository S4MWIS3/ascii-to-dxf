# ASCII → DXF

Convert images to ASCII art and export as DXF files for CAD and engraving applications.

## Features

✨ **Image to ASCII Conversion**
- Upload any image and convert it to ASCII art in real-time
- Multiple character sets: detailed ramp, dots, crosses, lines, geometric, numbers, braille, stipple, and custom
- Binary (foreground fill) mode with adjustable threshold

🎨 **Advanced Image Processing**
- Brightness & contrast controls
- Gamma correction for tone mapping
- Sharpening filter
- Dithering options: none, ordered (Bayer 4×4), Floyd-Steinberg, and Atkinson
- Image inversion toggle

📊 **Real-time Previews**
- Side-by-side original vs. adjusted image comparison
- Live tonal histogram with threshold visualization
- Adjustable ASCII preview font size
- Dark/light background modes

📐 **DXF Export**
- Export ASCII art as CAD-ready DXF files
- Customizable character height (mm) and width ratio
- Custom layer naming
- Perfect for CNC machines, laser cutters, and engravers

## Usage

1. **Upload an image** – Click or drag to upload a JPEG, PNG, or other image format
2. **Adjust settings** – Tweak resolution, image processing, and character set
3. **Preview** – See the result in real-time
4. **Export** – Download as `.dxf` file for use in CAD software

## Hosted Online

🌐 **Live version**: [https://S4MWIS3.github.io/ascii-to-dxf/](https://S4MWIS3.github.io/ascii-to-dxf/)

No installation needed – just open in your browser!

## Technical Details

- **Pure JavaScript** – No dependencies, works entirely in the browser
- **Local processing** – Images never leave your computer
- **Responsive design** – Works on desktop and tablet
- **High-quality dithering** – Multiple algorithms for different aesthetics

## Tips

- **Detailed ramp** charset works best with high-resolution images
- **Foreground fill** mode with Floyd-Steinberg dithering creates smooth gradients
- Lower **aspect correction** for horizontally stretched images
- Increase **character height** for larger physical output on CNC/laser
- **Sharpen** filter helps with low-contrast images

## License

MIT – feel free to fork, modify, and use however you like!
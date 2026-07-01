# 🎨 SpectraDrop

A beautiful, modern web application that extracts stunning color palettes from images using advanced pixel analysis.

## ✨ Features

- **🖼️ Drag & Drop Upload** - Simply drag your image onto the interface or use the file picker
- **🎯 Smart Color Extraction** - Intelligently extracts 5 dominant colors from your image
- **🏷️ Creative Color Names** - Generated names based on hue, saturation, and lightness (e.g., "Vivid Sky Blue")
- **📋 One-Click Copy** - Copy hex values to clipboard with instant feedback
- **📱 Responsive Design** - Works seamlessly on desktop and mobile devices
- **⚡ High Performance** - Efficient pixel sampling and color quantization
- **✨ Smooth Animations** - Delightful transitions and visual feedback

## 🚀 How to Use

1. **Open** the `inde.html` file in your web browser
2. **Upload an Image** by either:
   - Dragging and dropping an image onto the drop zone
   - Clicking "Browse Files" and selecting an image
3. **View Your Palette** - The app instantly generates and displays your color palette
4. **Copy Colors** - Click any hex value or color swatch to copy it to your clipboard

## 🎨 Supported Formats

- PNG
- JPG/JPEG

## 💻 Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Custom animations and Tailwind CSS framework
- **JavaScript** - Canvas API for pixel manipulation and color extraction
- **Canvas API** - Image processing and color quantization

## 🔍 How It Works

The Color Palette Generator uses advanced algorithms to:

1. **Load Image** - Reads the uploaded image data
2. **Sample Pixels** - Intelligently samples pixels across the image
3. **Quantize Colors** - Groups similar colors to reduce noise and identify true dominant colors
4. **Sort by Frequency** - Ranks colors by how often they appear
5. **Generate Names** - Creates human-readable color names based on color theory
6. **Display Results** - Shows colors with hex codes and creative names

## 🛠️ Technical Details

### Color Extraction Algorithm
- Skips transparent and near-white/black pixels for better results
- Quantizes colors to reduce noise (rounds to nearest 10)
- Samples every 4th pixel for performance optimization
- Returns top 5 most frequent colors

### Color Naming System
- Uses HSL (Hue, Saturation, Lightness) color space
- Generates descriptive names based on:
  - **Hue** - Red, Orange, Yellow, Green, Blue, etc.
  - **Saturation** - Vivid, Rich, Bright, Soft, Muted, Dusty
  - **Lightness** - Light, Deep descriptors

## 📦 File Structure

```
Color Theif/
├── inde.html        # Main HTML file
├── styles.css       # Stylesheet with animations and custom styles
└── README.md        # This file
```

## 🌐 Browser Compatibility

Works on all modern browsers that support:
- Canvas API
- FileReader API
- CSS Grid
- ES6 JavaScript

✅ Chrome/Edge ✅ Firefox ✅ Safari

## 💡 Tips & Tricks

- **Best Results**: Use high-quality images with distinct color regions
- **Fast Copying**: Click any color swatch for quick copy to clipboard
- **Toast Feedback**: Green notifications confirm successful color copies
- **Responsive**: The palette grid automatically adjusts to your screen size

## 🎯 Use Cases

- **Graphic Design** - Extract palettes from inspiration images
- **Web Design** - Build color schemes for websites
- **Branding** - Develop cohesive brand color palettes
- **Interior Design** - Match colors from photos to paint selections
- **Fashion** - Create clothing color combinations

## 🚀 Quick Start

```bash
# Simply open the file in your browser
# No installation or build process required!
open inde.html
```

## 📝 Notes

- The application runs entirely in the browser (client-side)
- No data is sent to external servers
- Images are processed locally on your machine
- Works offline once the page is loaded

---

**Created with ❤️ by Assem Bakr** | Made for designers, developers, and creative professionals

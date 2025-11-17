
# Photo Eraser Tool

A web-based application for precise image editing that allows you to selectively remove parts of images by drawing masks.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Browser](https://img.shields.io/badge/browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-lightgrey)

## ✨ Features

- **🎨 Dual Masking Modes**
  - **Draw Mask**: Mark areas to be removed (shown in red)
  - **Erase Mask**: Correct mistakes by erasing parts of the mask

- **🛠️ Interactive Controls**
  - Adjustable brush size (5px to 100px)
  - Undo/Redo functionality (up to 20 states)
  - Clear mask option
  - One-click download of processed images

- **👁️ Visual Feedback**
  - Real-time preview with transparency shown as checkered pattern
  - Custom cursors for different modes
  - Responsive design for desktop and mobile

- **⚡ Technical Features**
  - Canvas-based drawing with smooth strokes
  - Touch support for mobile devices
  - Firebase integration
  - PNG export with transparency preservation

## 🚀 Quick Start

### Online Usage
Simply open the HTML file in a modern web browser - no installation required!

### Local Development
1. Clone or download the HTML file
2. Open `index.html` in your web browser
3. Start editing images immediately

## 📖 How to Use

### Basic Workflow
1. **Upload Image**: Click "Upload Image" to load your photo
2. **Select Mode**: 
   - Use "Draw Mask" to mark areas for removal
   - Use "Erase Mask" to correct mistakes
3. **Adjust Brush**: Use the slider to set brush size (5-100px)
4. **Draw Mask**: Click and drag on the image
   - Red areas will become transparent
5. **Preview**: See results in real-time
6. **Download**: Click "Download" to save your edited image

### Advanced Features
- **Undo/Redo**: Correct mistakes with history tracking (Ctrl+Z/Ctrl+Y equivalents)
- **Clear Mask**: Start over with a clean slate
- **Mobile Support**: Touch-friendly interface for tablets and phones

## 🎯 Use Cases

- **📸 Photo Editing**: Remove unwanted objects from photos
- **🛒 E-commerce**: Create transparent backgrounds for product images
- **🎨 Graphic Design**: Prepare images for compositions
- **📱 Social Media**: Create custom images with transparent elements
- **🎮 Game Assets**: Edit sprites and textures

## 🛠️ Technical Details

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

### File Format Support
- **Input**: JPEG, PNG, GIF, WebP, BMP
- **Output**: PNG (with transparency preservation)

### Performance
- Optimized canvas rendering
- Memory-efficient history management (20 state limit)
- Responsive design for various screen sizes
- Touch-optimized drawing experience

## 📱 Mobile Usage

The application is fully responsive and supports:
- Touch gestures for drawing
- Mobile-optimized interface
- Adaptive brush sizes for different screen sizes
- Prevent default scrolling while drawing

## 🔧 Project Structure

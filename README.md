# 3D Cube Visualization Tool

An interactive web-based tool for visualizing and analyzing 3D cubes, perfect for solving aptitude questions involving 3D geometry and cube analysis problems.

## 🎯 Purpose

This tool was designed to help solve common aptitude test questions involving:
- **Painted cube problems** - Understanding how many small cubes have paint on different numbers of faces
- **Cube slicing analysis** - Calculating corner, edge, face, and internal cubes after slicing
- **Opposite and adjacent face relationships** - Visualizing spatial relationships between cube faces
- **Color pattern analysis** - Analyzing cubes with different color combinations

## ✨ Features

### 🎮 Interactive 3D Cube
- **Drag to rotate** - Click and drag or use touch gestures to rotate the cube in 3D space
- **Rotation controls** - Precise rotation buttons for X, Y, and Z axes
- **Auto-rotation mode** - Automatic spinning for demonstrations
- **Reset functionality** - Quick return to default viewing angle

### 🎨 Face Customization
- **Text/Number input** - Add any text or numbers to cube faces
- **Color picker** - Choose custom colors for each face
- **Face selection** - Click on faces or use buttons to select and edit
- **Visual highlighting** - Selected faces are highlighted with glowing borders

### 📊 Cube Slicing Analysis
- **Configurable slicing** - Set X, Y, Z slice counts (1-10 per dimension)
- **Visual grid lines** - Toggle grid overlays to see exact slice positions
- **Mathematical analysis** - Automatic calculation of:
  - Corner cubes (3 faces exposed)
  - Edge cubes (2 faces exposed)
  - Face cubes (1 face exposed)
  - Internal cubes (0 faces exposed)

### 🎲 Quick Presets
- **🎲 Dice Pattern** - Realistic dice with actual dot patterns (1-6)
- **🌈 Color Pattern** - Primary colors with descriptive labels
- **🔢 Number Pattern** - Simple numbered faces (1-6)
- **🔄 Opposite Pairs** - Shows opposite face relationships (A/A', B/B', C/C')
- **📚 Aptitude Test Pattern** - Common exam scenario with mixed colors

### 📱 Advanced Analysis Features
- **Color-based cube counting** - Shows how many small cubes have specific color combinations
- **Adjacent face analysis** - Visual representation of which faces touch each other
- **Opposite face mapping** - Clear identification of opposite face pairs
- **Comprehensive statistics** - Total cube counts with verification

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation
1. Download the `index.html` file
2. Open it in any web browser
3. Start using immediately - no setup required!

### Basic Usage
1. **Rotate the cube** - Click and drag to rotate, or use the rotation buttons
2. **Select a face** - Click on any cube face or use the face selection buttons
3. **Customize faces** - Add text/numbers and choose colors
4. **Analyze slicing** - Set slice dimensions and click "Analyze Cube Slices"
5. **Use presets** - Try the built-in patterns for common scenarios

## 📖 Use Cases

### Aptitude Test Questions
Perfect for solving questions like:
- "A cube is painted red and then cut into 27 smaller cubes. How many small cubes have paint on exactly 2 faces?"
- "If opposite faces of a cube are painted the same color, how many different types of small cubes are created when sliced 3×3×3?"

### Educational Purposes
- **Geometry visualization** - Help students understand 3D spatial relationships
- **Mathematical concepts** - Demonstrate cube properties and calculations
- **Interactive learning** - Hands-on exploration of 3D geometry

### Problem-Solving Practice
- **Competitive exams** - CAT, GRE, GMAT cube problems
- **Interview preparation** - Technical interview questions involving 3D thinking
- **Math competitions** - Olympiad-style geometry problems

## 🎲 Special Features

### Realistic Dice Dots
The dice preset shows authentic dice faces with proper dot patterns:
- **1**: Single center dot
- **2**: Diagonal corners
- **3**: Diagonal line
- **4**: Four corners
- **5**: Four corners + center
- **6**: Two columns of three

### Mobile Responsive Design
- **Touch controls** - Swipe to rotate on mobile devices
- **Responsive layout** - Adapts to different screen sizes
- **Optimized performance** - Smooth animations on all devices

### Grid Visualization
- **Slice preview** - See exactly where cuts will be made
- **Dynamic updates** - Grid lines update automatically with slice settings
- **3D accuracy** - Grid lines respect the 3D perspective of each face

## 🔧 Technical Details

### Technology Stack
- **HTML5** - Semantic structure and canvas support
- **CSS3** - 3D transforms, animations, and responsive design
- **Vanilla JavaScript** - No external dependencies
- **CSS Grid** - For dice dot layouts and responsive design

### Browser Compatibility
- ✅ Chrome 12+
- ✅ Firefox 10+
- ✅ Safari 4+
- ✅ Edge 12+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Features
- **Hardware acceleration** - Uses CSS 3D transforms for smooth animations
- **Efficient DOM manipulation** - Minimal redraws and optimized updates
- **Responsive design** - Adapts to screen size without performance loss

## 📊 Mathematical Accuracy

The tool uses precise mathematical formulas for cube analysis:

```
Total cubes = X × Y × Z slices

Corner cubes = 8 (maximum, may be less for small cubes)
Edge cubes = 4 × (X-2) + 4 × (Y-2) + 4 × (Z-2)
Face cubes = 2 × (X-2) × (Y-2) + 2 × (Y-2) × (Z-2) + 2 × (X-2) × (Z-2)
Internal cubes = (X-2) × (Y-2) × (Z-2)
```

All calculations include verification to ensure mathematical accuracy.

## 🎯 Pro Tips

### For Aptitude Questions
- Use **grid lines** to visualize slice positions accurately
- Try the **aptitude preset** for common exam scenarios
- Use **color analysis** to count cubes with specific paint combinations
- Check **adjacent face analysis** to understand spatial relationships

### For Learning
- Start with **simple 2×2×2** slicing to understand concepts
- Use **auto-rotation** to see all faces clearly
- Try different **color combinations** to distinguish faces easily
- Use **opposite pair preset** to learn face relationships

### For Problem Solving
- **Reset rotation** frequently to maintain orientation
- Use **face selection highlighting** to track which face you're editing
- **Toggle grid lines** on/off to see the cube both ways
- **Verify calculations** using the built-in mathematical analysis

## 🤝 Contributing

This is a single-file project designed for simplicity and portability. If you'd like to suggest improvements:
1. Test the current functionality thoroughly
2. Identify specific use cases or mathematical scenarios
3. Propose enhancements that maintain the single-file architecture
4. Ensure compatibility across different browsers and devices

## 📄 License

This project is open source and available for educational and personal use. Feel free to modify and distribute for non-commercial purposes.

## 🆘 Support

If you encounter any issues:
1. **Check browser compatibility** - Ensure you're using a modern browser
2. **Verify JavaScript is enabled** - The tool requires JavaScript to function
3. **Try different devices** - Test on both desktop and mobile
4. **Reset the cube** - Use the reset button if the cube gets into an odd state

## 🎓 Educational Value

This tool demonstrates several important concepts:
- **3D spatial reasoning** - Essential for engineering and mathematics
- **Geometric visualization** - Understanding how 2D views relate to 3D objects
- **Mathematical modeling** - Converting real-world problems into calculations
- **Interactive learning** - Hands-on exploration enhances understanding

Perfect for students, teachers, and anyone preparing for aptitude tests involving 3D geometry!

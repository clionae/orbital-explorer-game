# 🏛️ Nintendo 3DS Louvre Guide - Canva Export Kit

## 📋 What's Included

This export kit contains everything you need to recreate the Nintendo 3DS Louvre Guide interface in Canva:

### 🎮 Complete Interface Elements
- **Full 3DS Frame** - Authentic Nintendo 3DS hardware design
- **Top Screen** - Museum header and welcome content
- **Bottom Screen** - Scrollable tour selection interface
- **Hardware Buttons** - A/B buttons and D-pad with proper shading

### ⚛️ 3D Orbital Models
- **S Orbital** - Spherical with radial gradient
- **P Orbital** - Dumbbell shape with 3D effect
- **D Orbital** - Cloverleaf pattern with rotation
- **F Orbital** - Complex multi-lobed with conic gradient

### 🎨 Design System
- **Color Palette** - Complete Louvre museum colors
- **UI Components** - Tour cards, buttons, headers
- **Typography** - Museum-appropriate fonts and sizing

## 🚀 How to Use in Canva

### Step 1: Access the Export Kit
1. Open `canva-export.html` in your browser
2. This contains all the visual elements ready for export

### Step 2: Export Elements
**Method 1 - Screenshots:**
1. Take screenshots of individual sections
2. Crop to isolate specific components
3. Save as PNG files

**Method 2 - Browser Tools:**
1. Right-click on elements
2. Select "Save image as" (for CSS-generated graphics)
3. Use browser developer tools to export specific divs

### Step 3: Import to Canva
1. Open Canva and create a new design
2. Go to "Uploads" in the left sidebar
3. Upload your exported images
4. Drag and drop onto your canvas

### Step 4: Customize Your Design
1. **Replace placeholder text** with your orbital content
2. **Add real orbital photos** in the designated photo areas
3. **Maintain the color scheme** using provided hex codes
4. **Keep the 3DS proportions** for authenticity

## 🎨 Color Palette

Use these exact colors to maintain the Louvre museum theme:

```css
/* Primary Colors */
--louvre-gold: #d4af37      /* Main accent color */
--louvre-dark-gold: #b8941f /* Darker accent */
--museum-cream: #fef7e7     /* Light background */
--louvre-beige: #f4e4bc     /* Secondary background */
--museum-brown: #8b4513     /* Text color */
--orbital-orange: #ff9500   /* Orbital highlights */
```

## 📐 Dimensions & Specifications

### Nintendo 3DS Frame
- **Total Size:** 400px × 480px
- **Top Screen:** 360px × 200px
- **Bottom Screen:** 360px × 200px
- **Border Radius:** 20px (frame), 8px (screens)

### Orbital Models
- **S Orbital:** 100px diameter circle
- **P Orbital:** 120px × 60px dumbbell
- **D Orbital:** 80px × 80px rotated square
- **F Orbital:** 100px × 100px rounded square

### Buttons
- **Standard Button:** 120px × 40px
- **Hardware Buttons:** 30px diameter circles
- **Border Radius:** 8px (standard), 50% (hardware)

## 🖼️ Adding Real Orbital Photos

### Photo Placeholders
The interface includes 4 designated areas for real orbital images:
1. **Real orbital photograph** - Experimental images
2. **Data visualization** - Graphs and charts  
3. **Probability density plot** - Mathematical representations
4. **Quantum mechanical model** - Theoretical visualizations

### Photo Specifications
- **Size:** 150px × 120px recommended
- **Format:** PNG or JPG
- **Background:** Transparent or white
- **Border:** 2px dashed #d4af37 (amber)

## 🎯 Design Tips for Canva

### Maintaining Authenticity
1. **Keep the 3DS aspect ratio** - Don't stretch the frame
2. **Use museum colors consistently** - Stick to the palette
3. **Preserve button styling** - Maintain the 3D depth effect
4. **Keep text readable** - Use appropriate contrast

### Layout Guidelines
1. **Top Screen:** Header and main content
2. **Bottom Screen:** Interactive elements and navigation
3. **Hardware Buttons:** Keep positioned on the right side
4. **Spacing:** Maintain 20px padding inside screens

### Typography Recommendations
- **Headers:** Bold, 18-24px, Museum Brown (#8b4513)
- **Body Text:** Regular, 12-14px, Museum Brown (#8b4513)
- **Captions:** Light, 10-12px, Louvre Gold (#d4af37)

## 📱 Responsive Considerations

If creating multiple sizes for different platforms:

### Mobile Version
- Scale down proportionally
- Maintain button touch targets (minimum 44px)
- Keep text legible at smaller sizes

### Desktop Version  
- Can scale up to 800px × 960px maximum
- Maintain crisp edges on orbital models
- Ensure hardware buttons remain proportional

## 🔧 Technical Notes

### CSS Properties Used
- **Gradients:** `linear-gradient()`, `radial-gradient()`, `conic-gradient()`
- **Shadows:** `box-shadow` for depth and glow effects
- **Transforms:** `rotate()` for orbital orientations
- **Borders:** `border-radius` for rounded corners

### Browser Compatibility
- Modern browsers support all CSS features used
- Gradients render consistently across platforms
- Export as images for maximum compatibility

## 📞 Support

If you need help with the Canva integration:
1. Check the visual examples in `canva-export.html`
2. Use the provided color codes exactly as specified
3. Maintain the proportions and spacing guidelines
4. Reference the original live demo for interactions

## 🎉 Final Result

Your Canva design should perfectly replicate the Nintendo 3DS Louvre Guide aesthetic with:
- ✅ Authentic 3DS hardware appearance
- ✅ Museum-quality color scheme  
- ✅ Interactive-looking interface elements
- ✅ Professional orbital visualizations
- ✅ Space for your real orbital photographs

Perfect for educational presentations, chemistry assignments, or museum-style exhibits! 🏛️⚛️
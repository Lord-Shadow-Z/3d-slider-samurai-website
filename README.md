# 3d-slider-samurai-website
Samurai 3D Showcase Website A visually striking website featuring a 3D rotating gallery of samurai images with modern design elements. This project combines:  3D CSS Transformations: Showcases images in an auto- transform properties  Responsive Design: Adapts seamlessly across desktop, tablet, and mobile devices. 
# Samurai 3D Showcase Website

![Website Preview](preview.jpg) *(optional - add a screenshot later)*

A visually striking website featuring a 3D rotating gallery of samurai images with modern design elements.

## Features
- 🌀 Auto-rotating 3D image slider with perspective effects
- ✍️ Custom text styling with stroke effects
- 📱 Responsive layout with mobile optimizations
- 🎨 Subtle grid background pattern
- 👤 Model overlay for depth composition

## Installation

### Option 1: Simple Viewing
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/samurai-website.git
   ```
2. Open `index.html` in your web browser

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/samurai-website.git
   cd samurai-website
   ```
2. Install Live Server (for local testing):
   ```bash
   npm install -g live-server
   ```
3. Run the project:
   ```bash
   live-server
   ```
   The website will automatically open in your default browser at `http://127.0.0.1:8080`

## Project Structure
```
samurai-website/
├── index.html         # Main HTML file
├── style.css          # Stylesheet
└── image/             # Image assets
    ├── bg.png         # Background image
    ├── Model 2.png    # Character model
    ├── Cultivator.jpg # Gallery images
    └── ...
```

## Customization
To modify the image gallery:
1. Replace images in the `image/` folder
2. Update the HTML with your new image paths:
   ```html
   <div class="item" style="--position: 1">
     <img src="image/your-new-image.jpg" alt="">
   </div>
   ```
3. Adjust the `--quantity` value in the slider div to match your image count

## Technologies Used
- HTML5
- CSS3 (including 3D transforms and animations)
- Responsive design principles

## License
This project is open source and available under the [MIT License](LICENSE).

---

**Note:** For the best experience, please view this website in modern browsers that support CSS 3D transforms (Chrome, Firefox, Edge, Safari).

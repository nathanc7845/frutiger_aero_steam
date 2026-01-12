
---

# **Frutiger Aero Theme for Steam**

Clean and responsive theme with **Frutiger Aero** aesthetics for Steam using the **Millennium** framework.

## 🎨 Features

* ✨ Clean design in Frutiger Aero style
* 📱 Fully responsive
* 🎭 Glassmorphism effects (frosted glass)
* 🌊 Custom background (image 2)
* 🎯 Smooth transitions and animations
* 🌈 Vibrant color palette (blues, cyans and greens)
* 💫 Elegant hover effects

## 📦 Installation

### 1. **Install Millennium Steam**

* Download and install [Millennium Steam](https://github.com/SteamDeckHomebrew/PluginLoader) if you don’t have it yet.

### 2. **Add the background image**

* Create a folder named `images` inside the theme folder
* Add your background image (the mentioned image 2) as `background.jpg` inside the `images` folder
* Or edit the `theme.css` file and change the image path on line 25

### 3. **Install the theme**

* Copy the theme folder to Millennium’s themes directory
* Usually located at: `Steam/steamui/skins/`
* Activate the theme through Millennium’s settings

## 🎨 Customization

### Change the background image

Edit `theme.css` on line 25:

```css
background-image: url('./images/background.jpg') !important;
```

Replace it with the path to your own image.

### Adjust colors

Colors can be customized at the beginning of the `theme.css` file using CSS variables:

```css
:root {
  --frutiger-blue: #00B4D8;
  --frutiger-cyan: #48CAE4;
  --frutiger-sky: #90E0EF;
  --frutiger-green: #06D6A0;
  /* ... */
}
```

## 📱 Responsiveness

The theme is fully responsive and adapts to different screen sizes:

* **Desktop (> 1920px)**: Full layout with all effects
* **Laptop (1366px – 1920px)**: Optimized layout
* **Tablet (768px – 1366px)**: Adapted layout
* **Mobile (< 768px)**: Compact layout

## 🎯 Styled Elements

* ✅ Panels and windows (glassmorphism)
* ✅ Buttons (gradients and hover effects)
* ✅ Game cards
* ✅ Inputs and text fields
* ✅ Custom scrollbars
* ✅ Menus and context menus
* ✅ Notifications and badges
* ✅ Links and icons
* ✅ Tooltips

## 🛠️ File Structure

```
Frutiger Aero/
├── skin.json          # Theme configuration
├── theme.css          # Main styles
├── images/            # Images folder
│   └── background.jpg # Background image
└── README.md          # This file
```

## 📝 Notes

* Make sure Millennium Steam is installed
* The theme uses `!important` to override Steam’s default styles
* Some elements may require adjustments depending on your Steam version
* High-quality images are recommended for the background

## 🎨 Frutiger Aero Aesthetic

This theme incorporates key elements of the Frutiger Aero style:

* 🌊 Water and bubbles
* 🌍 Natural elements (sky, water, nature)
* 🏙️ Futuristic cities
* 💎 Glass and transparency effects
* 🌈 Vibrant colors and gradients
* ✨ Soft glow and reflections

## 📄 License

This theme is open-source and can be freely modified.

## 🙏 Credits

Theme created with inspiration from the Frutiger Aero aesthetic of the 2000–2010 era.

---

**Enjoy your Steam with Frutiger Aero style!** 🚀

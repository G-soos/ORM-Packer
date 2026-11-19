# 🔴🟢🔵 ORM Texture Packer & Splitter

Create, combine, and extract ORM textures (Occlusion, Roughness, Metallic) with ease.

This web tool allows you to:

- ✅ Pack maps for **Unreal / Godot / glTF (ORM)**, **Unity HDRP Mask Map**, **Unity URP/Built-in Metallic-Smoothness** or a custom layout
- ✅ Use an optional **alpha channel** (Height, Smoothness…) with exact, straight-alpha PNG output
- ✅ Drop all your maps at once — they are assigned by file name (`_AO`, `_Roughness`, `_Metallic`, `_Gloss`, `_Height`…)
- ✅ **Invert** any channel (Roughness ↔ Smoothness), automatically when needed
- ✅ Switch target and loaded maps are re-routed — convert ORM ⇄ Mask Map in seconds
- ✅ Split any packed texture into grayscale maps (downloaded as one .zip)
- ✅ Non-square, power-of-two friendly output (size = longest side) with high-quality downscaling
- ✅ Paste images with Ctrl+V, preview each channel, zoom 1:1
- ✔️ 100% in-browser — nothing is uploaded

If you like this and want to see development continue consider to

 <!-- Buy Me a Beer -->
  <a href="https://www.buymeacoffee.com/Gsoos">
    <img 
      src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20beer&emoji=%F0%9F%8D%BA&slug=Gsoos&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" 
      height="50"
    />
  </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <!-- PayPal Donate -->
  <a href="https://www.paypal.com/donate/?hosted_button_id=MKU4HJ2MHUNGJ">
    <img 
      src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" 
      height="50"
    />
  </a>



---

## 🚀 Main Features

### 🎯 Targets (presets)

| Target | R | G | B | A |
|---|---|---|---|---|
| ORM — Unreal / Godot / glTF / Blender | Occlusion | Roughness | Metallic | optional Height |
| Unity HDRP — Mask Map | Metallic | Occlusion | Detail Mask | Smoothness |
| Unity URP / Built-in — Metallic | Metallic | — | — | Smoothness |
| Custom | any | any | any | any |

### 🎨 Packer

- Load a map per channel (button, drag & drop, Ctrl+V) or set a solid value (0–255)
- Pick which part of the image to read (Gray / R / G / B / A) and invert it
- Size badge per map and a warning when sizes differ

### 🔧 Splitter

- Load any packed RGB/RGBA texture and get one grayscale map per channel
- Drag a channel into the packer, or **Send all to packer** and change the target to convert formats
- Download all channels as a single .zip

### 📦 Output

- Sizes 64 → 8192 (longest side, aspect ratio kept) or Original
- Resize filter: Smooth (area average / bilinear) or Nearest
- Lossless 8-bit PNG written pixel-exact (RGB, or RGBA when alpha is on)
- Automatic file name, e.g. `T_Rock_ORM.png`, `T_Rock_MaskMap.png`

---

## 🖥️ Interface

Built with:

- **HTML5**
- **TailwindCSS**
- **Vanilla JavaScript**
- **Canvas 2D API**

Features:

- Responsive layout (desktop and mobile)  
- Settings remembered between visits  
- Built-in guide and FAQ  

---

## 🧩 How to Use

1. Choose the **Target** for your engine
2. Drop your maps (or load them one by one / use solid values)
3. Check the preview (RGB or per channel)
4. Pick the output size and download

**Import tip:** packed masks are linear data — disable sRGB in Unreal/Unity and use *Non-Color* in Blender.

---

## 🌐 Share Preview (Open Graph)

The project includes OG metadata for:

- Thumbnail  
- Custom title  
- Description  

to generate rich previews on Discord, WhatsApp, Twitter, Facebook, Telegram, etc.

---

## 🧠 Technologies Used

- HTML5  
- TailwindCSS  
- Vanilla JavaScript  
- Canvas API  
- Open Graph meta tags  
- GitHub Pages  

---

## 📥 Download / Usage

- No installation required  
- Runs directly in any modern browser  

---

## ✨ Author

**Gsoos**  
Tools for 3D artists and developers.






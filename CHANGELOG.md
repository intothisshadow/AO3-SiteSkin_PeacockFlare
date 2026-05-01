# Changelog

All notable changes to this project will be documented in this file.



## [1.0.0] - 2026-05-01 (current)

**Theme Name:** Peacock Flare - AO3 Site Skin  
**Base:** Moonlit Wisteria by intothisshadow  
**Last Updated:** 2026-May-01 19:29 GMT  

### 🎨 Visual & Color Palette

- **Backgrounds:** Implemented a "Deep Teal Night" (`#0e2e2e`) primary background with "Abyssal Teal" cards and "Darkened Teal" nested surfaces.  
- **Accents:** Added a vibrant jewel-tone palette featuring "Peacock Teal" (`#1d8080`), "Fuchsia Bloom" (`#c4417a`), "Magenta Mist" (`#7a2a50`), and "Splattered Gold" (`#c9a05a`).  
- **Gradients:** Established custom linear gradients for key UI elements:
  - **Header:** Magenta Mist → Soft Emerald  
  - **Navigation & Sidebar:** Soft Emerald → Ocean Blue  
  - **Footer:** Ocean Blue → Abyssal Dark  

### 🖋️ Typography & Fonts

- **Primary Body:** Set to **Lora** (serif) for readability.  
- **Headers:** Set to **Cinzel** for a stylized, elegant look.  
- **Code:** Set to **Source Code Pro** (monospace).  
- **Headings:** Integrated a multi-tier gradient system for Workskin headings ($h1$ through $h6$), ranging from full peacock sweeps (Gold/Teal/Fuchsia) to muted Teal-Ink.  

### 🏷️ Tag System (Custom Pill Styling)

- **Warning Tags:** Vivid Magenta/Fuchsia gradient with Rose borders.  
- **Relationship Tags:** Luxurious Gold-on-Dark styling.  
- **Character Tags:** Deep Ocean Blue gradient.  
- **Fandom Tags:** Magenta/Fuchsia styling with Soft Rose text.  
- **Freeform/Additional Tags:** Muted Teal/Seafoam styling.  
- **Rating Tags:** Deep Abyssal backgrounds with Teal borders.  

### 🏗️ Layout & UI Enhancements

- **Header:** Completely redesigned with a hidden logo (text-only title) and a 6px multi-color border-image bottom edge.  
- **Work Blurbs:** Implemented a minimal "cardless" look for blurbs, using a horizontal gradient separator rather than a solid box, with a Soft Emerald hover effect.  
- **Comments:** Added a alternating "glow" effect for comment icons: Teal for odd-numbered comments and Rose for even-numbered comments.  
- **User Icons:** Added a dual-ring border effect using Teal and Rose.  
- **Sidebar/Dashboard:** Redesigned with a Soft Emerald/Ocean Blue gradient background and rounded (14px) corners.  

### 🛠️ Technical Details

- **Icons:** Integrated "Replace the AO3 Icons 2.0" by ZerafinaCSS.  
- **Variables:** Centralized all colors into a `:root` block for easy user customization.  
- **Performance:** Enabled antialiasing and `optimizeLegibility` for smoother text rendering across browsers.  **Note:** Users can resize the entire skin's text by adjusting the `--desktop-base` variable in Section 0.  

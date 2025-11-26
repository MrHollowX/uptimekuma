# 🚀 Uptime Kuma Modern Dark Theme

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![CSS](https://img.shields.io/badge/style-CSS3-orange)

A sleek, modern, "Glassmorphism" inspired CSS theme for [Uptime Kuma](https://github.com/louislam/uptime-kuma) status pages. This theme transforms the default utilitarian look into a premium, card-based dashboard with a deep slate color palette.

![Screenshot](screenshot.png)
*(Replace `screenshot.png` with your actual image)*

## ✨ Features

* **🌑 Deep Slate Palette:** Replaces the standard black/white with a rich `slate-900` background (inspired by Tailwind CSS).
* **🃏 Floating Cards:** Detaches monitors from their group containers, giving every service its own independent, floating card.
* **🧊 Glassmorphism:** Adds a translucent, blurred glass effect to the "System Status" banner.
* **🅰️ Modern Typography:** Imports and applies the **Inter** font family for clean, legible text.
* **🟢 Glowing Accents:** Replaces standard greens with a vibrant Emerald accent color.
* **📱 Responsive Design:** Custom adjustments for mobile to ensure uptime bars and labels stack correctly.
* **🖱️ Interactive UI:** subtle hover animations and lift effects on status cards.

## 🛠️ Installation

Applying this theme is very simple and requires **no server restarts**.

1.  Log in to your **Uptime Kuma** dashboard.
2.  Navigate to **Settings** > **Appearance**.
3.  Scroll down to the **Custom CSS** box.
4.  Copy the contents of [`theme.css`](./theme.css) from this repository.
5.  Paste the code into the box.
6.  Click **Save**.

## 🎨 Customization

The theme uses CSS variables (`:root`) at the top of the file, making it easy to change colors to match your own branding.

```css
:root {
    --bg-color: #0f172a;     /* Background */
    --card-bg: #1e293b;      /* Card Background */
    --text-primary: #f1f5f9; /* Main Text */
    --accent-color: #10b981; /* Status Green/Glow */
    /* ... */
}

<img width="3840" height="1991" alt="image" src="https://github.com/user-attachments/assets/726f3e09-3d9c-4440-a8d9-888e40ec1dd4" />

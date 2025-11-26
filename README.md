# 🚀 Uptime Kuma Modern Dark Theme

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![CSS](https://img.shields.io/badge/style-CSS3-orange)

A sleek, modern, "Glassmorphism" inspired CSS theme for [Uptime Kuma](https://github.com/louislam/uptime-kuma) status pages. This theme transforms the default utilitarian look into a premium, card-based dashboard with a deep slate color palette.

![Screenshot](screenshot.png)

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
```

## 🐛 Troubleshooting
"My groups still have a dark background box behind them." This theme explicitly targets the .shadow-box class used by Uptime Kuma to make group containers transparent. If you see a dark box behind your groups, ensure you have copied the full CSS, specifically this section:

```css

.shadow-box, .card {
    background-color: transparent !important;
    box-shadow: none !important;
    border: none !important;
}
```

## 🤝 Contributing
Feel free to open an issue or submit a pull request if you find any layout bugs or have suggestions for improvements!

Note: This is a 3rd party CSS theme and is not officially affiliated with Uptime Kuma.

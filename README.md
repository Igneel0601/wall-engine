<h1 align="center">wall-engine</h1>
<p align="center">
  <img src="https://img.shields.io/badge/made%20for-ArchLinux-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/wayland-ready-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Rofi-powered-critical?style=flat-square" />
</p>

<p align="center"><strong>Dynamic Wallpaper Switcher with Live Wallpaper Support, SDDM Sync & Thumbnail Previews</strong></p>

<p align="center">
  <img src="./preview.gif" width="100%"/>
</p>

---

## ✨ Features

- 🎨 **Beautiful GUI with Rofi** — Previews thumbnails with icons and titles.
- 🧠 **Smart Thumbnail Generation** — Automatically crops and centers both images and videos.
- 🎥 **Live Wallpaper Support** — Seamless `mpvpaper` integration.
- ⚙️ **Syncs with SDDM** — Updates blurred login screen background.
- 💡 **Wayland-first** — Designed for Hyprland + `swww`, works with other Wayland setups.
- 🔥 **Fast, Minimal, Scripted** — No bulky dependencies or GUIs.

---

## 🚀 Preview

<img src="./preview.png" width="100%"/>

---

## 🎬 Demo

https://github.com/user-attachments/assets/1211269a-af95-453e-9a80-422e070de750

---

## 🎬 Walls

![Image](https://github.com/user-attachments/assets/6c01149e-0a51-4913-832b-7ce684c59fe0)

---

## 🛠️ Requirements

Ensure the following tools are installed:

| Tool         | Purpose                        |
|--------------|--------------------------------|
| `rofi`       | Wallpaper selector GUI         |
| `swww`       | Static wallpaper manager       |
| `mpvpaper`   | Live wallpaper engine          |
| `ffmpeg`     | Video thumbnail extraction     |
| `ImageMagick`| Image processing               |
| `dunstify`   | Notification popup             |

## 🚀 Usage

```bash
# Clone this repository
git clone https://github.com/Igneel0601/wall-engine.git
cd wall-engine

# Copy the Rofi theme (optional, for prettier UI)
cp selector2.rasi ~/.config/rofi/

# Launch the wallpaper engine
./wall2.sh



# 🎯 OMNISENS | Advanced Sensitivity Engine

![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-1.2.0-blue)
![Status](https://img.shields.io/badge/status-stable-brightgreen)

**OMNISENS** is a high-precision mouse sensitivity and FOV converter designed for competitive gamers. It accounts for complex game engine behaviors, resolution aspect ratios, and DPI changes to preserve your muscle memory across different setups.

---

## 🚀 Features

* **Cross-Engine FOV Conversion**: Supports **Source Engine** (4:3 Base), **Vertical FOV** (R6 Siege/BF), and **Horizontal Actual**.
* **Resolution & Aspect Ratio Scaling**: Automatically adjusts sensitivity when switching between 16:9, 4:3 stretched, or ultra-wide resolutions.
* **DPI Compensation**: Seamlessly convert your sens when upgrading your mouse hardware.
* **Monitor Distance 0% (Focal Scaling)**: Uses the industry-standard method to keep your "Degrees per Pixel" feeling consistent.
* **Real-time Calculation**: Values update instantly as you type.

---

## 📐 The Math Behind

OMNISENS uses **Focal Length Scaling** to maintain perceived tracking speed:

$$\text{New Sens} = \text{Old Sens} \times \frac{\text{DPI}_{old}}{\text{DPI}_{new}} \times \frac{\tan(\frac{\text{FOV}_{target}}{2})}{\tan(\frac{\text{FOV}_{current}}{2})} \times \frac{\text{AR}_{target}}{\text{AR}_{current}}$$

This ensures that the physical distance on your mousepad translates to the same relative movement on your screen, regardless of stretching or zooming.

---

## 🔗 Connect with me

[![GitHub](https://img.shields.io/badge/GitHub-Adiru3-181717?style=for-the-badge&logo=github)](https://github.com/Adiru3)
[![YouTube](https://img.shields.io/badge/YouTube-@adiruaim-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@adiruaim)
[![TikTok](https://img.shields.io/badge/TikTok-@adiruhs-000000?style=for-the-badge&logo=tiktok)](https://www.tiktok.com/@adiruhs)
[![Donatello](https://img.shields.io/badge/Support-Donatello-orange?style=for-the-badge)](https://donatello.to/Adiru3)

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE). 
Feel free to contribute or fork for your own needs!

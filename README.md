# 📱 Flutter Icon Resizer

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Type](https://img.shields.io/badge/tool-Flutter--Helper-success)
![Technology](https://img.shields.io/badge/built%20with-HTML%20%7C%20JS%20%7C%20Tailwind-orange)

An elegant, lightweight, and browser-based tool designed to transform a single **512x512 PNG** image into the standard icon sizes required for Flutter projects (Android & Web).

## 🚀 Why this tool?

When developing Flutter apps, generating launcher icons manually can be tedious. This tool automates the resizing process, ensuring your icons meet the specific pixel requirements for different screen densities without leaving your browser.

## 🧪 Demo


[![Live Demo](https://img.shields.io/badge/Live-Demo-blue)](https://isaac-maker.github.io/Icon-Resizer-Flutter/)

## ✨ Features

* **Strict PNG Validation:** Only accepts `.png` files to ensure transparency and quality.
* **Tailored for Flutter:** Generates the exact sizes needed for Android mipmap folders:
    * `48x48` (mdpi)
    * `72x72` (hdpi)
    * `96x96` (xhdpi)
    * `144x144` (xxhdpi)
    * `192x192` (xxxhdpi)
* **High Quality:** Uses Canvas resampling for crisp results.
* **Privacy First:** Processing happens 100% locally in your browser. Your images are never uploaded to a server.
* **One-Click Export:** Downloads all icons bundled in a single `.zip` file.

## 🛠️ How to Use

1.  **Open** the `index.html` file in any modern browser.
2.  **Drag and drop** your high-resolution PNG (recommended 512x512).
3.  **Click "Generate Icons"**.
4.  **Extract** the downloaded `.zip` and move the images to your Flutter project's asset or res folders.

## 📂 Folder Mapping (Android Reference)

| Size | Density | Flutter/Android Path |
| :--- | :--- | :--- |
| 48x48 | mdpi | `android/app/src/main/res/mipmap-mdpi/` |
| 72x72 | hdpi | `android/app/src/main/res/mipmap-hdpi/` |
| 96x96 | xhdpi | `android/app/src/main/res/mipmap-xhdpi/` |
| 144x144 | xxhdpi | `android/app/src/main/res/mipmap-xxhdpi/` |
| 192x192 | xxxhdpi | `android/app/src/main/res/mipmap-xxxhdpi/` |

## 🛠️ Built With

* **HTML5 / Canvas** - Image processing.
* **Tailwind CSS** - Modern UI styling.
* **JSZip** - For bundling the assets.

## 📄 License

This project is licensed under the MIT License - feel free to use it for your personal or commercial Flutter projects!

---

*Created with ❤️ for the Flutter Community.*

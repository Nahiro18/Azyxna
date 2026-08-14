<div align="center">
    <img src='assets/images/icon.jpg' alt='AzyX Icon' style="border-radius: 50px; height: 300px; width: 300px;"/>
    <h1 style="font-size:2rem; font-weight:bold;">AzyX</h1>
  <a href="https://github.com/Nahiro18/Azyxna/releases"/>
    <img src="https://img.shields.io/github/downloads/Nahiro18/Azyxna/total.svg?color=white&labelColor=purple&style=for-the-badge" alt="Total Downloads"/></a>
    
  <a href="https://github.com/Nahiro18/Azyxna/releases/latest">
    <img src="https://img.shields.io/github/v/release/Nahiro18/Azyxna?color=white&labelColor=purple&style=for-the-badge" alt="Latest Release"/></a>
  <a href="https://github.com/Nahiro18/Azyxna/stargazers">
    <img src="https://img.shields.io/github/stars/Nahiro18/Azyxna?color=white&labelColor=purple&style=for-the-badge" alt="GitHub Stars"/>
  </a>
</div>
<div align="center">
   <a href="https://discord.gg/rDwNf4BYfz">
      <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&color=white&labelColor=purple&logoColor=white" alt="Discord"/></a>
   
   <a href="https://t.me/Azyxanime">
      <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&color=white&labelColor=purple&logoColor=white" alt="Telegram"/></a>
</div>


# 🎉 Azyx - An Anilist client 🎉

Welcome to Azyx – a modern, feature-rich platform designed for seamless content browsing. With a sleek UI, extensive customization options, and a smooth user experience, Azyx makes discovering and organizing your favorite media effortless. 🚀📚

## 🚀 Features That Set Azyx Apart

### 🎨 Custom Themes
- Personalize **Azyx** with **light**, **dark**, or **system themes**.
- Go beyond the basics with fully customizable **highlight colors** to make Azyx truly yours.

### 🌈 Dynamic Theming
- **Effortlessly switch** between themes that adapt to your mood or device settings.
- Azyx doesn’t just follow trends, it **adapts to you**!

### 🖌️ Material Design Excellence
- Designed with **Flutter**, inspired by **Google’s Material Design** principles.
- Experience a **clean**, **modern**, and **intuitive interface** that feels just right.

### 🔄 Cool UI Elements
- Enjoy **sleek animations**, **smooth transitions**, and **engaging visuals**.
- Elevate your viewing and reading experience with visuals that are **alive** and **responsive**.

## 🐧 Linux Desktop Compatibility / Compatibilidad de escritorio Linux

### Supported distributions / Distribuciones compatibles

The Linux build is a **x86_64 (glibc)** binary and runs on any desktop distribution with **`xdg-utils`** installed / El build de Linux es un binario **x86_64 (glibc)** y funciona en cualquier distribución de escritorio con **`xdg-utils`** instalado:

- **Ubuntu** / **Linux Mint** (Cinnamon, XFCE, MATE, GNOME) ✅
- **Debian** ✅
- **Fedora** / **RHEL**-based / basadas en RHEL ✅
- **Arch Linux** / **Manjaro** ✅
- **openSUSE** ✅
- Any other glibc-based x86_64 distro with a desktop environment / Cualquier otra distro x86_64 basada en glibc con escritorio ✅

> **Not supported / No soportado:** musl-based distros (e.g. Alpine Linux) and ARM/ARM64 builds (not provided) / distros basadas en musl (p. ej. Alpine Linux) y builds ARM/ARM64 (no se publican).

### Required system dependencies / Dependencias de sistema requeridas

Install the equivalent packages for your distribution / Instala los paquetes equivalentes para tu distribución:

**Debian / Ubuntu / Linux Mint:**
```bash
sudo apt install libmpv-dev libsecret-1-0 libwebkit2gtk-4.1-0
```

**Fedora / RHEL-based / basadas en RHEL:**
```bash
sudo dnf install mpv-libs libsecret webkit2gtk4.1
```

**Arch Linux / Manjaro:**
```bash
sudo pacman -S libmpv libsecret webkit2gtk-4.1 xdg-utils
```

**openSUSE:**
```bash
sudo zypper install libmpv1 libsecret-1-0 webkit2gtk4.1
```

### Notes / Notas
- `xdg-utils` is preinstalled on most desktop environments (GNOME, KDE, XFCE, Cinnamon, MATE) / `xdg-utils` viene preinstalado en la mayoría de los escritorios (GNOME, KDE, XFCE, Cinnamon, MATE).
- The **AniList login** opens your default browser and the app **auto-registers** the `azyx://` scheme handler on first login — no manual setup needed on any supported distribution / El **login de AniList** abre tu navegador predeterminado y la app **registra automáticamente** el esquema `azyx://` en el primer login — no requiere configuración manual en ninguna distribución compatible.
- The **VOE / YourUpload fix** works out of the box thanks to the public extension repository / El **fix de VOE / YourUpload** funciona de serie gracias al repositorio público de extensiones: `https://raw.githubusercontent.com/Nahiro18/mangayomi-extensions/main/anime_index.json`

---

<!-- <div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
<!--   <img src="https://github.com/user-attachments/assets/3d4a99da-b53b-43f7-aeb1-f1df3dae378e" alt="Screenshot 2" style="width: 49%; margin-bottom: 10px;" /> -->
<!--   <img src="https://github.com/user-attachments/assets/52a3b2be-292f-4cf0-b5a8-4f5c7ab427b7" alt="Screenshot 3" style="width: 49%; margin-bottom: 10px;" /> -->
<!--   <img src="https://github.com/user-attachments/assets/7e0b1e99-d58d-4b4d-8a97-5fb2a1974fcc" alt="Screenshot 4" style="width: 49%; margin-bottom: 10px;" /> -->
<!--  <img src="https://github.com/user-attachments/assets/432b7c2b-f290-4ed2-b4b2-ad22ba70055c" alt="Screenshot 1" style="width: 49%; margin-bottom: 10px;" /> -->
<!--   <img src="https://github.com/user-attachments/assets/acb8a7a0-7ace-4097-8220-11880ce8fbf0" alt="Screenshot 5" style="width: 49%; margin-bottom: 10px;" /> -->
<!-- </div> -->

## 💡 Why Azyx?

- 🌐 **All-in-One**: Enjoy both **anime** and **manga** in a single app.
- ✨ **Highly Customizable**: Create an experience that’s **uniquely yours**.
- ⚡ **Modern Design**: Built with the latest tools and technologies for a **smooth and intuitive** experience.

## 🔗 Useful Links

- 📥 **Downloads**: [GitHub Releases](https://github.com/Nahiro18/Azyxna/releases)
- 📸 **Screenshots**: [Screenshots Gallery](https://path-to-screenshots)
- 🛠️ **Source Code**: [Azyx Repository](https://github.com/Nahiro18/Azyxna)

## 📜 License

Azyx is open-sourced under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.

---

> 💬 **Need Help?** Feel free to open an issue or reach out. We're always here to help you enjoy your anime and manga journey! 🚀✨

---

Made with ❤️ by anime and manga lovers for anime and manga lovers. 🌸

<div align="center">

<img src="assets/banner.png" alt="GMLX SPICETIFY" width="100%" />

# GMLX SPICETIFY V3

**Injector & Client Customizer for Spotify**

[🇪🇸 Español](#-español) • [🇺🇸 English](#-english)

[Discord](https://discord.com/gmlx) • [TikTok](https://tiktok.com/@444_gmlx) • [Guns](https://guns.lol/4gemelo4) • [Instagram](https://instagram.com/derek_.try)

</div>

---

## 🇪🇸 Español

Instalador de escritorio con interfaz gráfica para instalar **Spicetify** y personalizar tu Spotify con un solo clic. Sin comandos a mano: abres el programa, eliges tu sistema y le das a instalar.

### ✨ Funciones

- Instalación de Spicetify con un solo clic
- Compatible con **Windows (PowerShell)** y **macOS / Linux (Shell)**
- Descarga directa del instalador oficial de Spotify (versión web)
- Consola en vivo para ver todo el proceso de instalación
- Botón para copiar el comando de instalación
- Interfaz en **español e inglés**
- Aviso automático si no se abre como administrador (Windows)

### 📋 Requisitos

- **Spotify oficial** (versión web, **NO** la de Microsoft Store). Spicetify no funciona con la versión de Microsoft Store.
- Conexión a internet
- Windows, macOS o Linux

### 🚀 Uso

1. Descarga `GMLX-Spicetify.exe` desde la sección de [Releases](../../releases).
2. Ábrelo. Si sale el aviso de administrador, ciérralo y ábrelo con clic derecho → **Ejecutar como administrador**.
3. Si aún no tienes Spotify, usa el botón **Descargar Spotify (.exe)** e instálalo.
4. Elige tu sistema operativo y presiona **Instalar Spicetify**.
5. Cuando termine, reinicia Spotify para aplicar los cambios.

> ⚠️ Windows SmartScreen puede mostrar "Windows protegió tu PC" porque el programa no está firmado. Pulsa **Más información → Ejecutar de todas formas**.

### 🛠️ Ejecutar desde el código

Necesitas [Node.js](https://nodejs.org) 18 o superior.

```bash
git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
cd TU_REPOSITORIO
npm install --save-dev electron electron-builder
npm start
```

### 📦 Crear el .exe

```bash
npm run build
```

El archivo queda en la carpeta `dist/` como `GMLX-Spicetify.exe`.

### 📁 Estructura

```
├── assets/
│   ├── banner.png
│   └── logo.png
├── index.html     # Interfaz
├── main.js        # Proceso principal (Electron)
├── preload.js     # Puente seguro entre la interfaz y Electron
└── package.json
```

### ❓ Problemas frecuentes

| Problema | Solución |
| --- | --- |
| Spicetify no funciona | Verifica que Spotify sea la versión web y no la de Microsoft Store. |
| La instalación falla | Revisa tu conexión y la salida de la consola dentro del programa. |
| Sale el aviso de administrador | Cierra el programa y ábrelo con **Ejecutar como administrador**. |

### 💬 Soporte

¿Encontraste un error o tienes ideas? Escríbelo en el canal de soporte de nuestro Discord. Si te sirvió, ¡compártelo!

### 🌐 Redes

♰〡[ᴅɪꜱᴄᴏʀᴅ](https://discord.com/gmlx)  
♰〡[ᴛɪᴋᴛᴏᴋ](https://tiktok.com/@444_gmlx)  
♰〡[ɢᴜɴꜱ](https://guns.lol/4gemelo4)  
♰〡[ɪɴꜱᴛᴀ](https://instagram.com/derek_.try)

### ⚖️ Aviso

Este proyecto no está afiliado a Spotify ni a Spicetify. Usa el instalador oficial de Spicetify y es responsabilidad de cada usuario cumplir los términos de Spotify.

---

## 🇺🇸 English

Desktop installer with a graphical interface to install **Spicetify** and customize your Spotify with a single click. No typing commands by hand: open the app, pick your system and hit install.

### ✨ Features

- One-click Spicetify installation
- Works on **Windows (PowerShell)** and **macOS / Linux (Shell)**
- Direct download of the official Spotify installer (web version)
- Live console to follow the whole installation process
- Button to copy the install command
- **Spanish and English** interface
- Automatic warning if it is not run as administrator (Windows)

### 📋 Requirements

- **Official Spotify** (web version, **NOT** the Microsoft Store one). Spicetify does not work with the Microsoft Store version.
- Internet connection
- Windows, macOS or Linux

### 🚀 Usage

1. Download `GMLX-Spicetify.exe` from the [Releases](../../releases) section.
2. Open it. If the administrator warning appears, close it and reopen with right click → **Run as administrator**.
3. If you don't have Spotify yet, use the **Download Spotify (.exe)** button and install it.
4. Pick your operating system and press **Install Spicetify**.
5. When it finishes, restart Spotify to apply the changes.

> ⚠️ Windows SmartScreen may show "Windows protected your PC" because the app is not signed. Click **More info → Run anyway**.

### 🛠️ Run from source

You need [Node.js](https://nodejs.org) 18 or higher.

```bash
git clone https://github.com/YOUR_USER/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
npm install --save-dev electron electron-builder
npm start
```

### 📦 Build the .exe

```bash
npm run build
```

The file is created in the `dist/` folder as `GMLX-Spicetify.exe`.

### 📁 Structure

```
├── assets/
│   ├── banner.png
│   └── logo.png
├── index.html     # User interface
├── main.js        # Main process (Electron)
├── preload.js     # Secure bridge between the UI and Electron
└── package.json
```

### ❓ Troubleshooting

| Problem | Fix |
| --- | --- |
| Spicetify doesn't work | Make sure Spotify is the web version and not the Microsoft Store one. |
| Installation fails | Check your connection and the console output inside the app. |
| Administrator warning shows up | Close the app and reopen it with **Run as administrator**. |

### 💬 Support

Found a bug or have ideas? Tell us in the support channel of our Discord. If it helped you, share it!

### 🌐 Socials

♰〡[ᴅɪꜱᴄᴏʀᴅ](https://discord.com/gmlx)  
♰〡[ᴛɪᴋᴛᴏᴋ](https://tiktok.com/@444_gmlx)  
♰〡[ɢᴜɴꜱ](https://guns.lol/4gemelo4)  
♰〡[ɪɴꜱᴛᴀ](https://instagram.com/derek_.try)

### ⚖️ Disclaimer

This project is not affiliated with Spotify or Spicetify. It uses the official Spicetify installer, and every user is responsible for complying with Spotify's terms.

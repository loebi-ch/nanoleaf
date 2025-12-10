# Nanoleaf

[![GitHub Release](https://img.shields.io/github/v/release/loebi-ch/nanoleaf?style=flat-square)](https://github.com/loebi-ch/nanoleaf/releases)
[![HACS](https://img.shields.io/badge/HACS-Custom-orange.svg?style=flat-square)](https://hacs.xyz/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Custom%20Integration-41bdf5?style=flat-square&logo=homeassistant)](https://www.home-assistant.io/)

**Nanoleaf** is an enhanced Home Assistant custom integration for Nanoleaf devices. It serves as a modern successor to the built-in core integration, adding support for the new **Nanoleaf Essentials** line and **4D Screen Mirroring** capabilities.

## ✨ Features & Improvements

While the built-in [Nanoleaf integration](https://www.home-assistant.io/integrations/nanoleaf/) works well for legacy panels, it lacks support for newer hardware generations and features. **Nanoleaf** fills this gap:

* **💡 Nanoleaf Essentials Support:** Full support for the new Essentials line (Bulbs and Lightstrips) using the updated Nanoleaf API.
* **📺 Screen Mirroring (Nanoleaf 4D):** Control your Nanoleaf 4D Screen Mirror camera directly from Home Assistant. You can now select Screen Mirror modes (1D, 2D, 3D, 4D) directly from the effect list in HA.
* **🔄 Backwards Compatible:** Fully supports all older Nanoleaf devices (Shapes, Canvas, Lines, etc.) supported by the original integration.
* **⚙️ Updated Backend:** Built on the `aionanoleaf2` library, which unifies communication with both the legacy API and the new Essentials API.

## 📥 Installation

### Option 1: HACS (Recommended)

1.  Open **HACS** in Home Assistant.
2.  Go to "Integrations".
3.  Click the three dots in the top right corner and select **"Custom repositories"**.
4.  Paste the repository URL: `https://github.com/loebi-ch/nanoleaf`
5.  Select **"Integration"** as the category.
6.  Click **Add**.
7.  Find **Nanoleaf** in the list and click **Download**.
8.  Restart Home Assistant.

### Option 2: Manual Installation

1.  Download the latest release from [GitHub Releases](https://github.com/loebi-ch/nanoleaf/releases).
2.  Extract the zip file.
3.  Copy the `nanoleaf` folder into your `config/custom_components/` directory.
4.  Restart Home Assistant.

## ⚙️ Configuration

1.  Go to **Settings** -> **Devices & Services**.
2.  Wait for Home Assistant to automatically discover your Nanoleaf devices.
3.  If not discovered automatically, click **"+ Add Integration"** and search for **Nanoleaf**.
4.  Follow the setup wizard to pair your devices (you may need to hold the power button on the device to authenticate).

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a feature request, please feel free to open an issue or submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
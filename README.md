<div align="center">

# 🚀 VCoder Mobile IDE

### *Next-Generation 100% Offline Code Editor & Enterprise IDE for Android*

[![Release](https://img.shields.io/github/v/release/VegaTechSoft/VCoder?color=00F5D4&label=Latest%20Release)](https://github.com/VegaTechSoft/VCoder/releases)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-38BDF8?logo=android)](https://www.android.com)
[![License](https://img.shields.io/badge/License-Commercial%20Mobile-FF007F)](#-license--credits)
[![Status](https://img.shields.io/badge/Status-v1.0.0%20Stable-4ADE80)](#)

---

[📥 Download Latest APK](#-download--installation) • [✨ Key Features](#-key-features) • [🎨 Custom Themes](#-custom-theme-extensions) • [📧 Support](#-contact--support)

</div>

---

## 🌟 About VCoder

**VCoder** is a high-performance, privacy-focused, 100% offline mobile IDE designed for programmers, software engineers, and web developers. Built on a custom lightweight WebKit editor engine, VCoder delivers a desktop-class coding experience on mobile devices without relying on cloud servers or internet connections.

---

## ✨ Key Features

### ⚡ 100% Offline Multi-Language Code Editor
* **Supported Languages**: Java, Kotlin, C, C++, JavaScript, TypeScript, Python, HTML, CSS, SQL, JSON, Markdown, XML.
* **Multi-Tab Workspace**: Switch between multiple open files with instant state preservation.
* **Smart Auto-Closing**: Auto-closes HTML/XML tags (`<div>` → `</div>`), brackets (`{}`, `[]`, `()`), and quote pairs.
* **Smart Enter Indentation**: Automatically carries line indentation forward and expands `{}` into indented 3-line blocks.

### 🎨 20 Premium Themes & Custom JSON Theme Engine
* **4 Theme Categories**: Dark, Light, Neon, and Neumorphic surface styles.
* **Local JSON Theme Installer**: Install custom `.json` themes directly from your device storage.
* **Dynamic Status Bar Contrast**: Automatic status bar icon contrast adjustments for light and dark themes.

### 🤖 VCoder AI Copilot (100% Offline LLM Engine)
* **Local AI Execution**: Runs offline Qwen 2.5 local model weights stored in internal storage.
* **Active File Context**: Automatically inspects active file name, language, and source code.
* **1-Tap Code Fix Injection**: Tap **"⚡ Apply to Editor"** on generated AI code snippets to apply fixes directly into active editor tabs.

### 🛠️ Professional Developer Tools
* **Visual Color Picker**: Live inline color swatches next to `#HEX` and `rgba(...)` color strings with RGB/Alpha sliders and preset palettes.
* **Code Folding**: Fold HTML/XML tags (`<section> ... </section>`) and curly braces (`{ ... }`) with zero line-height drift.
* **Universal Code Prettifier & Linter**: Multi-language auto-formatter and diagnostic linter for matching brackets and syntax checks.
* **Dual Scrolling System**: Smooth 60/120fps touch scrolling + touch-draggable custom floating overlay scrollbars with 1.5s auto-hiding.

---

## 📥 Download & Installation

1. Go to the **[Releases Page](https://github.com/VegaTechSoft/VCoder/releases/latest)**.
2. Download the latest **`VCoder-v1.0.0-release.apk`**.
3. Open the downloaded file on your Android device and confirm installation.
4. Launch **VCoder** and start coding offline!

---

## 🎨 Custom Theme Extensions

VCoder supports custom `.json` theme extensions. You can create your own theme file and install it directly via **Extensions Manager → Install Extension → Browse .JSON File**.

### Example Theme JSON Format:

{
  "id": "theme_custom_neon",
  "name": "Custom Neon Glow",
  "version": "1.0.0",
  "author": "Vega Coder Developer",
  "description": "Custom neon theme installed from local storage.",
  "type": "THEME",
  "isInstalled": true,
  "isEnabled": true,
  "isBuiltIn": false,
  "config": {
    "colors": {
      "headerBg": "#12002B",
      "headerText": "#FF007F",
      "headerSubtext": "#00F5D4",
      "bodyBg": "#0D0221",
      "leftNavBg": "#12002B",
      "leftNavText": "#E0AAFF",
      "rightNavBg": "#12002B",
      "rightNavText": "#E0AAFF",
      "panelHeaderBg": "#1E0038",
      "panelBodyBg": "#0D0221",
      "panelText": "#E0AAFF",
      "accentColor": "#FF007F",
      "inputBg": "#0D0221",
      "inputText": "#00F5D4",
      "inputHint": "#7B2CBF",
      "iconTint": "#00F5D4",
      "statusBg": "#12002B",
      "statusText": "#00F5D4",
      "buttonBg": "#1E0038",
      "buttonText": "#FF007F",
      "dialogBg": "#12002B",
      "dialogText": "#E0AAFF",
      "tabActiveBg": "#1E0038",
      "tabActiveText": "#00F5D4",
      "tabInactiveBg": "#0D0221",
      "tabInactiveText": "#7B2CBF",
      "backgroundColor": "#0D0221",
      "lineNumberBackgroundColor": "#12002B",
      "lineNumberColor": "#7B2CBF",
      "textColor": "#E0AAFF",
      "keywordColor": "#FF007F",
      "stringColor": "#00F5D4",
      "commentColor": "#7B2CBF",
      "numberColor": "#FFE600",
      "functionColor": "#00F5D4"
    }
  }
}



## 📄 License

Copyright © 2025 **VegaTech Software Studios**. All Rights Reserved.

This software is provided for personal and professional use as a compiled binary.
Unauthorized copying, reverse engineering, redistribution, or modification of this 
application and its assets is strictly prohibited.

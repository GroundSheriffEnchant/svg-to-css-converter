# 🎨 SVG to CSS Converter

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,17,23&height=210&section=header&text=SVG%20to%20CSS%20Converter&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Turn%20Vector%20Graphics%20into%20Pure%20CSS%20Art&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.9.0-C77DFF?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Node](https://img.shields.io/badge/Node.js-20+-7B2CBF?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![License](https://img.shields.io/badge/license-MIT-9D4EDD?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Output](https://img.shields.io/badge/output-SCSS%20%7C%20LESS%20%7C%20Tailwind-E0AAFF?style=for-the-badge&logo=sass&logoColor=black)](https://github.com)

<br/>

### ⚡ Convert SVG icons and shapes into clean, scalable CSS — no images required

*🎯 Pixel-Perfect • 🎨 Pure CSS • 🧩 Zero Runtime • 🚀 Lightweight*

<br/>

<a href="https://share.google/KNO65rYEFiln1mGMo">
  <img src="https://img.shields.io/badge/🚀_TRY_CONVERTER-C77DFF?style=for-the-badge&logo=googlechrome&logoColor=black&labelColor=9D4EDD" alt="Try Converter" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/KNO65rYEFiln1mGMo">
  <img src="https://img.shields.io/badge/📥_INSTALL-7B2CBF?style=for-the-badge&logo=npm&logoColor=white&labelColor=5A189A" alt="Install" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/KNO65rYEFiln1mGMo">
  <img src="https://img.shields.io/badge/📚_DOCS-9D4EDD?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=6A0DAD" alt="Docs" height="45"/>
</a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**SVG to CSS Converter** is a fast, developer-friendly tool that transforms **SVG vector graphics** into **pure CSS code**. Instead of shipping heavy `.svg` files or bloating your HTML with inline markup, generate lightweight CSS rules that render your icons and shapes perfectly in any browser.

Ideal for **design systems**, **icon libraries**, **micro-interactions**, and **performance-critical frontends** where every byte counts.

> 💡 **Why pure CSS?** Smaller bundles, easier theming, no network requests, and icons that scale infinitely with no quality loss.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎨 **Pure CSS Output** | 📦 **Multi-Format** | 🧩 **Zero Runtime** |
|:---:|:---:|:---:|
| Clean, readable<br/>CSS rules | SCSS, LESS, Tailwind,<br/>plain CSS | No JS, no library,<br/>no dependencies |

| 🎯 **Pixel-Perfect** | 🌈 **CSS Variables** | ⚡ **Batch Mode** |
|:---:|:---:|:---:|
| Preserves every curve<br/>and color | Auto-generated<br/>theme variables | Convert entire<br/>folders at once |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tool

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎨 **Truly Pure CSS** | Generates `background-image`, `mask`, `clip-path` & `box-shadow` rules — no images |
| 📉 **Bundle-Size Saver** | Reduce icon payload by up to 80% compared to SVG sprite sheets |
| 🌈 **Theme-Ready** | Uses CSS custom properties so you can recolor icons with one variable |
| ⚡ **Blazing Fast** | Converts 1,000+ icons in under 3 seconds with the CLI |
| 🧩 **Framework-Agnostic** | Works with React, Vue, Svelte, Angular, plain HTML — anything |
| 🛡️ **Battle-Tested** | Handles gradients, masks, filters & multi-path SVGs correctly |

<img width="1200" height="630" alt="svg-to-css-014a0c3e" src="https://github.com/user-attachments/assets/619bf5bb-30e4-446c-82b0-70def127a8db" />


</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Conversion Preview

<div align="center">

```css
/* 🎨 Generated from icon.svg */

.icon-heart {
  --icon-color: #ff4757;
  display: inline-block;
  width: 24px;
  height: 24px;
  background-color: var(--icon-color);
  mask-image: url("data:image/svg+xml,...");
  mask-size: contain;
  mask-repeat: no-repeat;
  mask-position: center;
}

/* ✅ Pure CSS • 🎯 Pixel-perfect • 🌈 Themeable */
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎨 svg-to-css-converter/
├── 🎯 src/
│   ├── parser/                # SVG parsing & optimization
│   │   ├── svg-parser.ts
│   │   └── optimizer.ts
│   ├── converters/            # Output generators
│   │   ├── plain-css.ts
│   │   ├── scss.ts
│   │   ├── less.ts
│   │   └── tailwind.ts
│   ├── cli/                   # Command-line interface
│   └── api/                   # Optional web API
├── 🌐 web/                    # Browser playground
├── 🧪 tests/                  # Snapshot & visual tests
└── 📖 docs/                   # Usage & configuration
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![SVGO](https://img.shields.io/badge/SVGO-3E7CB1?style=for-the-badge&logo=svg&logoColor=white)
![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found an SVG that doesn't convert? Want a new output format?

<div align="center">

<a href="https://share.google/KNO65rYEFiln1mGMo">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/KNO65rYEFiln1mGMo">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-C77DFF?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>
<a href="https://share.google/KNO65rYEFiln1mGMo">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-7B2CBF?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🎨 Made with 💜 by the SVG to CSS Team

*If this tool shrank your bundle — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,17,23&height=120&section=footer" width="100%"/>

</div>

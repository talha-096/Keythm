<a name="readme-top"></a>

<div align="center">
  <h1>⌨️ Keythm</h1>
  <p><strong>A modern typing test application with realistic mechanical keyboard audio feedback and real-time WPM tracking.</strong></p>

  <p>
    <a href="https://github.com/talha-096/Keythm"><strong>Website: https://github.com/talha-096/Keythm »</strong></a>
    <br />
    <br />
    <a href="https://github.com/talha-096/Keythm/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/talha-096/Keythm/issues">Request Feature</a>
  </p>

  <p>
    <a href="https://github.com/talha-096">
      <img src="https://img.shields.io/badge/Made%20by-Talha-556bf2?style=for-the-badge&logo=github&logoColor=white" alt="Made by Talha">
    </a>
    <a href="https://github.com/talha-096/Keythm/stargazers">
      <img src="https://img.shields.io/github/stars/talha-096/Keythm?style=for-the-badge&logo=github&color=gold" alt="GitHub Stars">
    </a>
    <a href="https://github.com/talha-096/Keythm/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/talha-096/Keythm?style=for-the-badge&color=blue" alt="License">
    </a>
  </p>
</div>

<br />

## 📑 Table of Contents

- [About The Project](#about-the-project)
- [✨ Key Features](#-key-features)
- [🛠 Tech Stack](#-tech-stack)
- [🧰 Getting Started](#-getting-started)
- [📜 Available Scripts](#-available-scripts)
- [👤 Author](#-author)
- [📄 License](#-license)

<br />

## About The Project

**Keythm** is a sleek, web-based typing speed application built with Next.js 16, React 19, and Tailwind CSS. It features **realistic mechanical keyboard audio feedback**, real-time WPM/accuracy tracking, multiple color themes, interactive virtual keyboard displays, and detailed performance breakdown charts.

Website: [https://github.com/talha-096/Keythm](https://github.com/talha-096/Keythm)

<br />

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| **Mechanical Audio** | Realistic per-key audio synthesis powered by Web Audio API |
| **Multiple Test Modes** | Practice with Time presets (15s–120s), Word counts, Quotes, or Zen mode |
| **On-Screen Keyboard** | Interactive virtual keyboard highlighting active keystrokes in real time |
| **Comprehensive Analytics** | Track WPM, raw speed, accuracy, consistency, character breakdown, and WPM-over-time charts |
| **Theme Customization** | 6 color themes — Classic, Mint, Royal, Dolch, Sand, and Scarlet |
| **Font Picker** | 9 developer-centric fonts (Geist Mono, JetBrains Mono, Fira Code, Space Grotesk, etc.) |
| **Custom Settings** | Sound volume control, live stats toggle, ghost mode, and faah audio mode |

<br />

## 🛠 Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **UI Core**: [React 19](https://react.dev/), [Tailwind CSS v4](https://tailwindcss.com/)
- **Primitives**: [Base UI](https://base-ui.com/), [shadcn/ui](https://ui.shadcn.com/)
- **Animations**: [Motion](https://motion.dev/)
- **Charts**: [Recharts](https://recharts.org/)
- **Database & ORM**: [Drizzle ORM](https://orm.drizzle.team/) + LibSQL / Turso
- **Linter & Formatter**: [Biome](https://biomejs.dev/)

<br />

## 🧰 Getting Started

### Prerequisites
Make sure you have Node.js (v20+) or Bun installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/talha-096/Keythm.git
   cd Keythm
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   Create a `.env.local` file in the project root:
   ```env
   DATABASE_URL=libsql://dummy-db.turso.io
   DATABASE_AUTH_TOKEN=dummy_auth_token_for_local_development_12345
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

<br />

## 📜 Available Scripts

| Script | Description |
| :--- | :--- |
| `npm run dev` | Starts the Next.js development server |
| `npm run build` | Builds the application for production |
| `npm run start` | Starts the production server |
| `npm run lint` | Lints code using Biome |
| `npm run format` | Formats codebase with Biome |
| `npm run typecheck` | Validates TypeScript types |

<br />

## 👤 Author

Developed by **Talha**

- Website: [https://github.com/talha-096/Keythm](https://github.com/talha-096/Keythm)
- GitHub: [@talha-096](https://github.com/talha-096)
- Repository: [Keythm](https://github.com/talha-096/Keythm)

<br />

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

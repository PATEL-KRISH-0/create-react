# 🚀 create-codecafe

**A sleek CLI tool to scaffold modern React + Vite projects with beautiful starter templates in seconds.**

Powered by [CodeCafé ☕](https://www.youtube.com/@CodeCafe-24-7), this CLI helps you skip the messy setup and dive straight into building awesome projects — with your favorite UI tools like TailwindCSS, Bootstrap, and Remix Icons.

---

## ✨ Features

- ⚡ One-command Vite + React setup
- 🎨 Choose from Tailwind, Bootstrap, or Remix Icons
- 🧠 Smart prompts with `--interactive` mode
- 🔧 Git initialization and dependency installation
- 🎯 CDN-based assets for fast setup
- 🤩 Beautiful terminal UI (chalk + ora + boxen)
- 🧩 CLI flags for automation and scripting

---

## 📦 Installation

Use `npx` to run without installing globally:

```bash
npx create-codecafe my-app
```

This will:

- 📁 Clone the default template (React + Vite + Remix Icons)
- 📦 Install dependencies
- 🔧 Initialize Git
- ✅ Display next steps

---

## 🧠 Interactive Mode

```bash
npx create-codecafe my-app --interactive
```

You’ll be prompted to:

- Choose a template: `default`, `tailwind`, `bootstrap`
- Initialize Git? ✅ or ❌
- Install dependencies? ✅ or ❌

---

## ⚙️ Command-Line Flags

| Flag            | Description                                                  |
|------------------|--------------------------------------------------------------|
| `--interactive` | Enable interactive prompts                                   |
| `--template`    | Choose template: `default`, `tailwind`, `bootstrap`          |
| `--no-install`  | Skip dependency installation                                 |
| `--no-git`      | Skip Git initialization                                      |

---

## 📁 Templates

Templates are hosted at:  
🔗 [PATEL-KRISH-0/create-react](https://github.com/PATEL-KRISH-0/create-react)

```
create-react/
└── templates/
    ├── default/     → React + Vite + Remix Icons
    ├── tailwind/    → React + Vite + Tailwind (CDN)
    └── bootstrap/   → React + Vite + Bootstrap (CDN)
```

Each template includes:

- `index.html` with correct links
- `src/` folder with starter components
- `vite.config.js`, `package.json`, etc.

---

## 🚀 Getting Started

### ✅ Basic Project (Zero Config)

```bash
npx create-codecafe my-project
```

- Uses default template
- Installs dependencies
- Initializes Git

### 🔄 Full Interactive Setup

```bash
npx create-codecafe my-project --interactive
```

- Choose template
- Enable/disable Git
- Enable/disable install

---

## 🧪 Example Commands

```bash
# Default template with all setup
npx create-codecafe my-app

# Tailwind, no Git
npx create-codecafe my-ui --template tailwind --no-git

# Bootstrap, skip install
npx create-codecafe admin-dashboard --template bootstrap --no-install

# Full interactive setup
npx create-codecafe --interactive
```

---

## 🛠️ Local Development & Contribution

```bash
git clone https://github.com/PATEL-KRISH-0/create-codecafe
cd create-codecafe
npm install
npm link
```

Then test it:

```bash
create-codecafe test-app --interactive
```

To publish new version:

```bash
npm version patch
npm publish
```

---

## 🖌️ Tech Stack

- [`degit`](https://github.com/Rich-Harris/degit) - GitHub template cloning
- [`chalk`](https://www.npmjs.com/package/chalk) - Colored CLI logs
- [`ora`](https://www.npmjs.com/package/ora) - CLI spinners
- [`boxen`](https://www.npmjs.com/package/boxen) - Boxed messages
- [`prompts`](https://www.npmjs.com/package/prompts) - Interactive CLI
- [`minimist`](https://www.npmjs.com/package/minimist) - Argument parsing

---

## ❤️ Made by CodeCafé

Created with ☕ by [CodeCafé](https://www.youtube.com/@CodeCafe-24-7)  
We build real-world tools, UI kits, and developer-first utilities.

If you liked this tool:

- ⭐ Star the repo on GitHub
- 📦 Share it on npm
- ☕ Support the channel on YouTube

---

## 📜 License

MIT © [Krish / CodeCafé](https://www.youtube.com/@CodeCafe-24-7)

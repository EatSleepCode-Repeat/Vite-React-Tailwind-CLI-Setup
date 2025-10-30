# 🚀 Vite + React + Tailwind Setup Script

<div align="center">

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**A beautiful, interactive CLI tool to quickly scaffold Vite + React + Tailwind CSS projects**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Screenshots](#-demo) • [Contributing](#-contributing)

</div>

---

## ✨ Features

- 🎨 **Interactive Menu System** - Beautiful, colorful CLI interface with easy navigation
- ⚡ **Quick Project Setup** - Create new Vite + React projects with Tailwind CSS in seconds
- 🔧 **Existing Project Support** - Add Tailwind CSS to your existing Vite projects
- 📦 **Dependency Manager** - Install popular packages like React Router, Axios, Framer Motion, and more
- 🎯 **Pre-configured** - Automatically sets up Tailwind config, CSS imports, and demo components
- ✅ **Error Handling** - Validates prerequisites and provides helpful error messages
- 🌈 **Styled Demo Component** - Includes a beautiful example component to verify everything works

## 📋 Prerequisites

Before using this script, ensure you have the following installed:

- **Node.js** (v14 or higher)
- **npm** (comes with Node.js)
- **Zsh** shell (default on macOS, installable on Linux)

## 🔧 Installation

### Option 1: Quick Install

```bash
# Create the scripts directory if it doesn't exist
mkdir -p ~/.zsh-scripts

# Add to your .zshrc
echo "source ~/.zsh-scripts/vite-setup.zsh" >> ~/.zshrc

# Reload your shell configuration
source ~/.zshrc
```

### Option 2: Manual Install

1. Clone this repository or download `vite-setup.zsh`
2. Move it to `~/.zsh-scripts/` (create the directory if needed)
3. Add this line to your `~/.zshrc`:

   ```bash
   source ~/.zsh-scripts/vite-setup.zsh
   ```

4. Reload your shell: `source ~/.zshrc`

## 🚀 Usage

Simply run the command in your terminal:

```bash
vite-setup
```

### Menu Options

#### 1️⃣ Create New Project

Creates a brand new Vite + React + Tailwind CSS project from scratch:

- Scaffolds Vite project with React template
- Installs all dependencies automatically
- Configures Tailwind CSS
- Sets up a beautiful demo component
- Ready to run with `npm run dev`

#### 2️⃣ Setup Existing Project

Adds Tailwind CSS to an existing Vite + React project:

- Installs Tailwind dependencies
- Creates configuration files
- Updates CSS imports
- Must be run from the project root directory

#### 3️⃣ View Configuration Details

Displays information about:

- Tech stack overview
- Available npm scripts
- Project file structure
- Quick reference guide

#### 4️⃣ Install Additional Dependencies

Choose from popular packages:

- **React Router DOM** - Client-side routing
- **Axios** - HTTP client for API calls
- **React Icons** - Popular icon library
- **Framer Motion** - Animation library
- **Zustand** - Lightweight state management
- Or install any custom package

#### 5️⃣ Exit

Returns you to your terminal

## 📸 Demo

```
╔═══════════════════════════════════════════╗
║   Vite + React + Tailwind CSS Setup      ║
║              Menu System                  ║
╚═══════════════════════════════════════════╝

1. Create new project
2. Setup existing project
3. View configuration details
4. Install additional dependencies
5. Exit

Enter your choice [1-5]:
```

## 🎯 Example Workflow

```bash
# Run the setup script
vite-setup

# Choose option 1 (Create new project)
# Enter project name: my-awesome-app

# Wait for setup to complete...

# Navigate to your project
cd my-awesome-app

# Start development server
npm run dev
```

Your project will include a beautiful demo page with:

- Gradient background
- Styled card component
- Tailwind utility classes in action
- Responsive design

## 📁 Generated Project Structure

```
my-project/
├── src/
│   ├── App.jsx          # Pre-styled demo component
│   ├── index.css        # Tailwind directives
│   └── main.jsx         # Entry point with CSS import
├── tailwind.config.js   # Tailwind configuration
├── postcss.config.js    # PostCSS configuration
├── vite.config.js       # Vite configuration
├── index.html
└── package.json
```

## 🛠️ What Gets Configured

### Tailwind Config (`tailwind.config.js`)

```javascript
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### CSS (`src/index.css`)

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Demo Component

A beautiful example component showcasing Tailwind's utility classes with:

- Gradient backgrounds
- Shadow effects
- Hover states
- Responsive design

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 🐛 Bug Reports

If you find a bug, please open an issue with:

- Your OS and shell version
- Node.js and npm versions
- Steps to reproduce
- Expected vs actual behavior

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- [React](https://react.dev/) - A JavaScript library for building user interfaces
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- Inspired by the need for quick, beautiful project scaffolding

## 📧 Contact

Have questions or suggestions? Feel free to reach out!

---

<div align="center">

**Made with ❤️ by [Chris](https://github.com/eatsleepcode-repeat)**

⭐ Star this repo if you find it helpful!

</div>


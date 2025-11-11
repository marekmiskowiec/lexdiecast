# LexDiecast Collector

A website showcasing a collection of diecast car models. Built with Astro, offering fast and optimized user experience.

## 🚗 About the Project

LexDiecast Collector is a showcase website for a diecast car collection, containing over 1000 models in stock. The site presents different types of models, a photo gallery, and information about the collection.

## ✨ Features

- **Header** - Hero section with main title and background
- **Intro** - Introduction to the collection
- **About** - About section
- **CarTypes** - Presentation of different model types (Mainline, Premium, etc.)
- **Gallery** - Photo gallery of models
- **Footer** - Site footer

## 🛠️ Technologies

- [Astro](https://astro.build) - Framework for building fast websites
- HTML/CSS - Styling and structure
- Font Awesome - Icons

## 📦 Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd lexdiecast
```

2. Install dependencies:

```bash
npm install
```

## 🚀 Getting Started

### Development Mode

Run the development server on `localhost:4321`:

```bash
npm run dev
```

### Production Build

Build the project to the `./dist/` folder:

```bash
npm run build
```

### Preview Build

Preview the built version locally before deployment:

```bash
npm run preview
```

## 📁 Project Structure

```
/
├── public/              # Static files (images, favicon)
├── src/
│   ├── components/      # Astro components
│   │   ├── Header.astro
│   │   ├── Intro.astro
│   │   ├── About.astro
│   │   ├── CarTypes.astro
│   │   ├── Gallery.astro
│   │   └── Footer.astro
│   ├── layouts/         # Page layouts
│   │   └── BasicLayout.astro
│   ├── pages/           # Pages (routing)
│   │   └── index.astro
│   └── styles/          # Global styles
│       └── global.css
├── astro.config.mjs     # Astro configuration
└── package.json
```

## 🎨 Styling

The project uses CSS variables to manage colors and styles. Main styles are located in `src/styles/global.css`, and each component can have its own styles in the `<style>` section.

## 📝 npm Scripts

| Command             | Action                   |
| :------------------ | :----------------------- |
| `npm install`       | Install dependencies     |
| `npm run dev`       | Start development server |
| `npm run build`     | Build production project |
| `npm run preview`   | Preview built version    |
| `npm run astro ...` | Run Astro CLI commands   |

## 🔧 Configuration

Astro configuration is located in the `astro.config.mjs` file. You can adjust project settings there according to your needs.

## 📄 License

This project is private property.

## 👤 Author

LexDiecast Collector

---

For more information about Astro, check out the [documentation](https://docs.astro.build) or join the [Discord](https://astro.build/chat).

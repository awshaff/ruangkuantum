# Ruang Kuantum

A modern, minimalist Hugo website built with the Paper theme. This site serves as a platform for quantum physics content, discussions, and educational resources.

## 🚀 Quick Start

### Prerequisites

- [Hugo](https://gohugo.io/getting-started/installing/) (extended version recommended)
- [Git](https://git-scm.com/downloads)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/awshaff/ruangkuantum.git
cd ruangkuantum
```

2. Initialize and update the theme submodule:
```bash
git submodule update --init --recursive
```

3. Start the development server:
```bash
hugo server -D
```

4. Open your browser and visit `http://localhost:1313`

## 📁 Project Structure

```
ruangkuantum/
├── archetypes/          # Content templates
├── assets/              # Site assets (CSS, JS, images)
├── content/             # Site content (posts, pages)
├── data/                # Data files
├── i18n/                # Translation files
├── layouts/             # Custom layout templates
├── public/              # Generated site (don't edit manually)
├── static/              # Static files
├── themes/              # Hugo themes
│   └── paper/           # Paper theme
├── hugo.toml            # Site configuration
└── README.md            # This file
```

## ⚙️ Configuration

The main configuration is in `hugo.toml`. Key settings include:

```toml
baseURL = 'https://ruangkuantum.web.id/'
languageCode = 'en-us'
title = 'Ruang Kuantum'
theme = 'paper'

[params]
  # Customize your site appearance and behavior
  color = 'linen'
  # Add social media links, analytics, etc.
```

## 📝 Creating Content

### New Post
```bash
hugo new posts/my-new-post.md
```

### New Page
```bash
hugo new about.md
```

Content files use Markdown with front matter:
```yaml
---
title: "My New Post"
date: 2025-07-01
draft: false
tags: ["quantum", "physics"]
---

Your content here...
```

## 🎨 Theme Features

This site uses the [Paper theme](https://github.com/nanxiaobei/hugo-paper) which provides:

- ⚡️ **Fast**: Optimized for speed and performance
- 👒 **Customizable**: Easy to customize colors and layout
- 🫙 **Smooth**: Clean, minimalist design
- 📱 **Responsive**: Works great on all devices
- 🌙 **Dark Mode**: Built-in dark/light mode toggle

## 🚀 Deployment

### Build for Production
```bash
hugo --minify
```

### Deploy to GitHub Pages
1. Enable GitHub Pages in your repository settings
2. Set up GitHub Actions workflow (see `.github/workflows/`)
3. Push to main branch to trigger deployment

### Deploy to Netlify
1. Connect your repository to Netlify
2. Set build command: `hugo --minify`
3. Set publish directory: `public`

### Deploy to Vercel
1. Import your repository to Vercel
2. Vercel will automatically detect Hugo and configure deployment

## 🛠️ Development

### Adding Custom Styles
1. Create CSS files in `assets/css/`
2. Include them in your templates or configuration

### Custom Layouts
1. Create layout files in `layouts/`
2. Override theme templates as needed

### Data Files
1. Add data files to `data/` directory
2. Access them in templates with `{{ .Site.Data }}`

## 📋 Available Commands

| Command | Description |
|---------|-------------|
| `hugo server` | Start development server |
| `hugo server -D` | Start server including draft content |
| `hugo` | Build site for production |
| `hugo --minify` | Build and minify site |
| `hugo new` | Create new content |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Hugo](https://gohugo.io/) - The world's fastest framework for building websites
- [Paper Theme](https://github.com/nanxiaobei/hugo-paper) - Beautiful and minimal Hugo theme
- [Quantum Physics Community](https://example.com) - Inspiration and content guidance

## 📞 Support

If you have any questions or need help:

- 📧 Email: contact@ruangkuantum.com
- 🐛 Issues: [GitHub Issues](https://github.com/yourusername/ruangkuantum/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/yourusername/ruangkuantum/discussions)

---

Made with ❤️ and ⚛️ quantum physics

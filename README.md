# Magierg's Blog

[![Deploy Hugo site to Pages](https://github.com/magierg/magierg.github.io/actions/workflows/hugo.yml/badge.svg)](https://github.com/magierg/magierg.github.io/actions/workflows/hugo.yml)

Personal blog and resume built with Hugo and deployed on GitHub Pages.

## 🚀 Live Site

Visit the blog at: [https://magierg.github.io](https://magierg.github.io)

## 🛠️ Tech Stack

- **[Hugo](https://gohugo.io/)** - Static site generator
- **[PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)** - Clean and responsive theme
- **GitHub Pages** - Hosting
- **GitHub Actions** - CI/CD pipeline for automated deployment

## 📝 Local Development

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version)
- Git

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/magierg/magierg.github.io.git
   cd magierg.github.io
   ```

2. Initialize the theme submodule:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server --buildDrafts
   ```

4. Open your browser to `http://localhost:1313`

### Creating New Content

- Create a new blog post:
  ```bash
  hugo new content posts/your-post-title.md
  ```

- Create a new page:
  ```bash
  hugo new content your-page-name.md
  ```

## 🚀 Deployment

The site is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` branch.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

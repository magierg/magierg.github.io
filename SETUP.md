
# invertassert.dev — QA & AI Blog Setup Guide

Welcome to the setup guide for **invertassert.dev** — a blog dedicated to Quality Assurance, Testing, and working with AI in software development.

## Steps to Enable GitHub Pages:

1. **Go to your GitHub repository**: https://github.com/magierg/magierg.github.io
2. **Click on "Settings"** tab in your repository
3. **Scroll down to "Pages"** in the left sidebar
4. **Configure the source**:
   - Source: "GitHub Actions"
   - This will allow the GitHub Actions workflow to deploy your site
5. **Save the settings**

## What Happens Next:

- The GitHub Actions workflow will automatically build and deploy your Hugo blog
- Your blog will be available at: https://invertassert.dev
- Every time you push changes to the main branch, the site will automatically rebuild and deploy

## Adding New Blog Posts:

To create new blog posts about QA, testing, or AI:

```bash
# Navigate to your repository
cd /Users/gierg/repos/magierg.github.io

# Create a new post
hugo new content/posts/your-topic-title.md

# Edit the post in your favorite editor
# Set draft = false when ready to publish

# Test locally
hugo server --buildDrafts

# Commit and push to deploy
git add .
git commit -m "Add new blog post: Your Topic Title"
git push origin main
```

## Branding & Theme Customization:

- The site is branded as **invertassert.dev** — focused on QA, test automation, and AI in software engineering
- You can customize the PaperMod theme by:
  - Editing `hugo.toml` for site configuration (update title, description, social links, etc.)
  - Adding custom CSS in `assets/css/extended/`
  - Modifying layouts in `layouts/` (overrides theme defaults)

## Example Topics to Cover

- Automated testing strategies
- AI-assisted QA workflows
- Test frameworks and tools
- Prompt engineering for testers
- Real-world QA case studies
- Integrating AI into CI/CD pipelines

Your QA & AI blog is now ready to go at **invertassert.dev**! 🚀

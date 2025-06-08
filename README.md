# Mahee's Blog

A personal blog built with Jekyll - a static site generator that transforms plain text into beautiful, static websites. This blog serves as a platform to share thoughts, knowledge, and experiences with the world.

## About This Project

- **Type**: Static website/blog
- **Framework**: Jekyll 4.4.1
- **Theme**: Minima
- **Purpose**: Personal blogging platform for sharing ideas and knowledge
- **Deployment**: GitHub Pages with custom domain
- **Live Site**: [blog.mahee.me](https://blog.mahee.me/)

## Prerequisites

Before running this project locally, ensure you have the following installed:

- **Ruby** version 2.7.0 or higher
- **RubyGems** (Ruby package manager)
- **Bundler** gem
- **GCC and Make** (for compiling native extensions)

For detailed installation instructions for your operating system, visit the [Jekyll Installation Guide](https://jekyllrb.com/docs/installation/).

## Quick Start

### 1. Clone and Navigate
```bash
# Clone the repository (if not already done)
git clone <repository-url>
cd my-blog
```

### 2. Install Dependencies
```bash
# Install Jekyll and Bundler if not already installed
gem install jekyll bundler

# Install project dependencies
bundle install
```

### 3. Run the Development Server
```bash
# Build the site and start the local server
bundle exec jekyll serve

# For live reload (automatically refresh on changes)
bundle exec jekyll serve --livereload
```

### 4. View Your Site
Open your browser and navigate to [http://localhost:4000](http://localhost:4000)

**Having issues?** Check the [Jekyll Troubleshooting Guide](https://jekyllrb.com/docs/troubleshooting/) for common problems and solutions.

## Project Structure

- `_posts/` - Blog posts in Markdown format
- `_sass/` - Sass stylesheets
- `_site/` - Generated static site (don't edit directly)
- `assets/` - Static assets (CSS, images, etc.)
- `_config.yml` - Site configuration
- `index.markdown` - Homepage content

## Creating New Posts

Create new blog posts in the `_posts/` directory with the naming convention:
```
YYYY-MM-DD-title-of-post.markdown
```

## Deployment

This blog is automatically deployed to GitHub Pages and served at [blog.mahee.me](https://blog.mahee.me/).

**How Automatic Deployment Works:**
- **Source Branch**: `main` branch is configured as the publishing source
- **Build Process**: GitHub Pages automatically builds Jekyll sites when changes are pushed
- **Deployment Trigger**: Any push to the `main` branch triggers automatic rebuild and deployment
- **Build Time**: Typically takes 1-2 minutes after push
- **Custom Domain**: Configured via `CNAME` file in repository root

**Deployment Flow:**
1. Push changes to `main` branch
2. GitHub Pages detects changes and starts Jekyll build
3. Site is automatically built and deployed to blog.mahee.me
4. Changes are live within minutes

- **Hosting**: [GitHub Pages](https://pages.github.com/)
- **Custom Domain**: blog.mahee.me
- **Repository**: [MaheeGamage/my-blog](https://github.com/MaheeGamage/my-blog)

For custom domain setup, see [GitHub Pages Custom Domain Guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Learn More

- [Jekyll Quick Start Guide](https://jekyllrb.com/docs/) - Official quick start guide
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Jekyll Step-by-Step Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/)
- [Minima Theme Documentation](https://github.com/jekyll/minima)

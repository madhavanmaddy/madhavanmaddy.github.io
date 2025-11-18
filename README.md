# Tech Blog

A technical blog built with Jekyll and hosted on GitHub Pages.

## Features

- Built with [Jekyll](https://jekyllrb.com/)
- Uses the [Minima](https://github.com/jekyll/minima) theme
- Automated deployment via GitHub Actions
- Syntax highlighting for code blocks
- SEO optimized with jekyll-seo-tag
- RSS feed support

## Local Development

### Prerequisites

- Ruby (version 3.1 or higher recommended)
- Bundler gem

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/madhavanmaddy/madhavanmaddy.github.io.git
   cd madhavanmaddy.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Build and serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Writing a New Post

1. Create a new file in the `_posts/` directory with the naming convention:
   ```
   YYYY-MM-DD-post-title.md
   ```

2. Add YAML front matter to your post:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS -0000
   categories: tech category-name
   ---
   ```

3. Write your content in Markdown below the front matter.

4. Commit and push to trigger automatic deployment via GitHub Actions.

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions whenever you push to the `main` branch. No manual deployment steps are required.

## Project Structure

```
.
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog posts directory
├── .github/
│   └── workflows/       # GitHub Actions workflows
├── Gemfile              # Ruby dependencies
├── index.md             # Homepage
├── about.md             # About page
└── README.md            # This file
```

## Customization

- Edit `_config.yml` to customize site settings, theme options, and plugins
- Modify `index.md` and `about.md` to personalize your homepage and about page
- Add custom layouts, includes, and styles in `_layouts/`, `_includes/`, and `assets/` directories (if needed)

## Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Minima Theme](https://github.com/jekyll/minima)

## License

This blog content is licensed under your chosen license. Feel free to use this setup as a starting point for your own blog.




# Website

This is the official website for Streaks (For YNAB), built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

### Prerequisites

- Ruby 2.6 or higher
- Bundler gem

### Local Development

1. **Fork and clone:**

```bash
git clone https://github.com/YOUR-USERNAME/streaks-for-ynab-website.git
cd streaks-for-ynab-website
```

2. **Install dependencies:**

   ```bash
   bundle install
   ```

3. **Start the development server:**

   ```bash
   bundle exec jekyll serve
   ```

4. **View the site:** Open [http://localhost:4000](http://localhost:4000) in your browser.

### Local Development with Base URL

If you encounter issues with the base URL configuration, use the development config:

```bash
bundle exec jekyll serve --config _config.yml,_config_dev.yml
```

This overrides the base URL for local testing.

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

# Website

This is the official website for Streaks (For YNAB), built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

### Prerequisites

- Ruby 2.6 or higher
- Bundler gem

### Local Development

1. **Install dependencies:**

   ```bash
   bundle install
   ```

2. **Start the development server:**

   ```bash
   bundle exec jekyll serve
   ```

3. **View the site:** Open [http://localhost:4000](http://localhost:4000) in your browser.

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

## 📞 Support

For website issues, **submit an issue**:
[Report problems](https://github.com/streaks-for-ynab/Website/issues)

## 📄 License

This website repository is open source and available under the MIT License. However, the main
Streals (For YNAB) iOS app repository is private and proprietary.

### What's Open Source

✅ This website's repository

### What's Private

- ❌ Streaks (For YNAB) iOS app source code
- ❌ App-specific business logic
- ❌ Internal development tools

---

_Built with Jekyll and hosted on GitHub Pages_

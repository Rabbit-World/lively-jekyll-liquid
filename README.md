# Lively Wallpaper - Dynamic Jekyll Template with Liquid

This is a Jekyll template for the Lively Wallpaper website with Liquid templating and multilingual support (English and Italian).

## Features

- Dynamic content rendering using Liquid templating
- Multilingual support (English and Italian)
- Configured for GitHub Pages deployment
- Preserves all styling, images, and functionality of the original site
- Modular structure with reusable components

## Structure

- `_config.yml`: Jekyll configuration
- `_layouts/`: Layout templates
- `_includes/`: Reusable components for different page sections
  - `controls/`: Modular control components for different wallpaper types
  - `header.html`: Header component with navigation
  - `footer.html`: Footer component
- `_data/`: Data files for translations and content
  - `languages.yml`: Language-specific translations
- `assets/`: Static assets (CSS, JS, images)
- `index.html`: Main page (English)
- `it.html`: Italian version of the main page

## Dynamic Content Features

This template uses Liquid templating to create a more dynamic and maintainable site:

1. **Modular Components**: Page sections are broken into reusable includes
2. **Dynamic Loops**: Uses Liquid loops to generate repetitive content
3. **Translation System**: Centralized translation management
4. **Conditional Rendering**: Content adapts based on the selected language

## Deployment Instructions

### Local Development

1. Install Ruby and Jekyll (if not already installed):
   ```
   gem install bundler jekyll
   ```

2. Install dependencies:
   ```
   cd lively-jekyll-liquid
   bundle install
   ```

3. Run the development server:
   ```
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### GitHub Pages Deployment

1. Create a new GitHub repository

2. Push this template to the repository:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR-USERNAME/lively-jekyll-liquid.git
   git push -u origin main
   ```

3. Configure GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages"
   - Select "main" branch as the source
   - Save the settings

4. Your site will be published at `https://YOUR-USERNAME.github.io/lively-jekyll-liquid/`
# Shopify Theme - Thermal Styling Brush Store

This repository contains the theme code for the Thermal Styling Brush Shopify store.

## Development Setup

### Prerequisites
- Node.js and npm installed
- Shopify CLI installed (`npm install -g @shopify/cli @shopify/theme`)

### Getting Started

1. **Clone the repository**
   ```bash
   git clone <your-github-repo-url>
   cd shopify-theme
   ```

2. **Authenticate with Shopify**
   ```bash
   shopify auth login
   ```

3. **Start local development server**
   ```bash
   shopify theme dev --store=fy5dcx-su.myshopify.com
   ```

4. **Open your browser** to the provided local URL (usually `http://127.0.0.1:9292`)

### Development Workflow

- **Local Development**: Make changes to files in your local repository
- **Live Preview**: Changes are automatically synced to a preview theme
- **Deploy**: Use `shopify theme push` to deploy changes to your live theme

### File Structure

- `assets/` - CSS, JavaScript, and image files
- `config/` - Theme configuration files
- `layout/` - Layout templates
- `locales/` - Translation files
- `sections/` - Reusable sections
- `snippets/` - Reusable code snippets
- `templates/` - Page templates

### Commands

- `shopify theme dev` - Start development server with live preview
- `shopify theme push` - Deploy changes to live theme
- `shopify theme pull` - Download latest theme files
- `shopify theme list` - List all themes in your store

### Store Information
- **Store**: fy5dcx-su.myshopify.com
- **Live Theme ID**: 186548617590
- **Theme Name**: LaunchYourStore-Thermal Styling Brush

## Contributing

1. Create a new branch for your changes
2. Make your changes locally
3. Test using the development server
4. Commit and push your changes
5. Create a pull request

## Deployment

To deploy changes to your live theme:

```bash
shopify theme push --store=fy5dcx-su.myshopify.com --theme=186548617590
```

**Note**: Always test changes in development mode before deploying to production.

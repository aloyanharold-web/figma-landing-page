# Figma Design Implementation

A responsive web implementation of a Figma design with desktop layout, featuring multiple image layers and positioned elements.

## 🚀 Live Demo

This project is deployed on GitHub Pages. Visit the live site to see the design in action.

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and layout
├── images/             # Design assets from Figma
│   ├── background-image.png
│   ├── overlay-image.png
│   ├── icon-1.png
│   ├── icon-2.png
│   └── icon-3.png
├── .github/workflows/  # GitHub Actions for deployment
└── README.md          # This file
```

## 🎨 Design Features

- **Responsive Layout**: 1440px × 3079px desktop design
- **Layered Images**: Multiple image layers with precise positioning
- **Circular Icons**: Three positioned circular elements with drop shadows
- **Mobile Responsive**: Scales appropriately for smaller screens

## 🛠️ Local Development

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd figma-design
   ```

2. Start a local server:
   ```bash
   python3 server.py
   ```

3. Open your browser and visit `http://localhost:8000`

## 📦 Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. Simply push to the main branch and the site will be updated automatically.

### Manual Deployment

1. Push your changes to the main branch
2. GitHub Actions will automatically build and deploy
3. Your site will be available at `https://<username>.github.io/<repository-name>`

## 🔧 Customization

To update the design with new Figma assets:

1. Update the Figma file
2. Use the Figma MCP tools to download new assets
3. Replace the images in the `images/` directory
4. Commit and push changes

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
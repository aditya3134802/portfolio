# Aditya Kumar Singh - Portfolio Website

Professional portfolio website for Cloud & DevOps Engineer with automated deployment using GitHub Actions and GitHub Pages.

## Live Website

🌐 **Visit:** https://aditya3134802.github.io/portfolio

## Project Structure

- `/index.html` - Main portfolio website
- `/src/images/` - Profile photo and assets
- `/.github/workflows/deploy.yml` - GitHub Actions workflow for deployment
- `/vercel.json` - Vercel deployment configuration (optional)

## Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Built with Tailwind CSS and Font Awesome icons
- **Interactive Elements** - Smooth scrolling, mobile menu, and hover effects
- **Professional Sections**:
  - Hero section with professional photo
  - About me with key metrics
  - Technical skills categorized by domain
  - Professional experience timeline
  - Featured projects showcase
  - Contact form and social links
- **Automated Deployment** - Deploys automatically to GitHub Pages on push

## Quick Start

### 1. Fork This Repository

Click the "Fork" button on GitHub to create your own copy.

### 2. Enable GitHub Pages

1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "GitHub Actions"
4. The site will automatically deploy when you push changes

### 3. Customize Your Content

Edit `index.html` to update:
- Personal information and contact details
- Professional experience
- Skills and technologies
- Project descriptions
- Social media links

### 4. Add Your Photo

Replace `src/images/profile.png` with your professional headshot.

## Deployment

The website automatically deploys to GitHub Pages when you:
- Push changes to the `main` branch
- Manually trigger the workflow from the Actions tab

### Deployment URL

Your portfolio will be available at:
`https://[your-username].github.io/[repository-name]`

## Local Development

To preview changes locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Customization

### Colors and Styling

The website uses Tailwind CSS. Key color scheme:
- Primary: Blue (#2563eb) to Purple (#7c3aed) gradient
- Background: Light gray (#f3f4f6)
- Text: Dark gray (#374151)

### Sections

- **Hero**: Introduction with photo and call-to-action buttons
- **About**: Professional summary with key statistics
- **Skills**: Technical expertise organized by category
- **Experience**: Timeline of professional roles
- **Projects**: Showcase of key projects and technologies
- **Contact**: Contact information and social links

### Contact Form

The contact form uses `mailto:` links to open the user's default email client with pre-filled information.

## Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Professional icons
- **GitHub Pages** - Free static website hosting
- **GitHub Actions** - Automated deployment

## Performance

- Fully static website for fast loading
- Responsive images and optimized assets
- Modern CSS with efficient animations
- Mobile-first responsive design

## Browser Support

Supports all modern browsers including:
- Chrome, Firefox, Safari, Edge
- Mobile browsers on iOS and Android

## License

This project is open source and available under the MIT License.
   
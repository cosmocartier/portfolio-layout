# Juno Watts Portfolio Website

A modern, animated personal portfolio website built with vanilla HTML, CSS, and JavaScript. Features smooth animations powered by GSAP, interactive elements, and a responsive design.

![Juno Watts Portfolio](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/License-ISC-blue)
![Vite](https://img.shields.io/badge/Build%20Tool-Vite-orange)
![GSAP](https://img.shields.io/badge/Animations-GSAP-green)

## 🚀 Live Demo

Visit the live website: [Juno Watts Portfolio](https://your-deployment-url.com)

## ✨ Features

- **Smooth Animations**: Advanced scroll-triggered animations using GSAP
- **Interactive Menu**: Animated hamburger menu with overlay navigation
- **Page Transitions**: Custom transition effects between pages
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean, minimalist design with bold typography
- **Performance Optimized**: Fast loading with Vite build tool
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🛠️ Tech Stack

- **Frontend**: Vanilla HTML, CSS, JavaScript
- **Build Tool**: [Vite](https://vitejs.dev/) - Fast development server and build tool
- **Animations**: [GSAP (GreenSock)](https://greensock.com/gsap/) - Professional animation library
- **Smooth Scrolling**: [Lenis](https://github.com/studio-freight/lenis) - Smooth scrolling library
- **Deployment**: Configured for Vercel deployment

## 📁 Project Structure

```
juno-watts/
├── css/                    # Stylesheets for each page
│   ├── home.css           # Home page styles
│   ├── about.css          # About page styles
│   ├── work.css           # Work page styles
│   ├── project.css        # Project page styles
│   ├── contact.css        # Contact page styles
│   ├── menu.css           # Navigation menu styles
│   ├── transition.css     # Page transition styles
│   └── footer.css         # Footer styles
├── script/                # JavaScript modules
│   ├── home.js            # Home page functionality
│   ├── about.js           # About page functionality
│   ├── work.js            # Work page functionality
│   ├── project.js         # Project page functionality
│   ├── contact.js         # Contact page functionality
│   ├── menu.js            # Menu interactions
│   ├── transition.js      # Page transitions
│   ├── lenis-scroll.js    # Smooth scrolling setup
│   ├── anime.js           # Animation utilities
│   └── slides.js          # Slide functionality
├── public/                # Static assets
│   ├── global/            # Global images and icons
│   ├── symbols/           # Decorative symbols
│   ├── about/             # About page images
│   ├── work/              # Work page images
│   └── project/           # Project page images
├── index.html             # Home page
├── about.html             # About page
├── work.html              # Work page
├── project.html           # Project page
├── contact.html           # Contact page
├── package.json           # Dependencies and scripts
├── vite.config.js         # Vite configuration
├── vercel.json            # Vercel deployment config
└── globals.css            # Global styles
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** (version 16 or higher)
- **npm** or **yarn** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/cosmocartier/portfolio-layout.git
   cd portfolio-layout
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the website

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run host` - Start development server with network access

## 🎨 Pages Overview

### 1. Home Page (`index.html`)
- Hero section with animated cards
- Skills showcase with scrolling animations
- Call-to-action sections
- Footer with contact information

### 2. About Page (`about.html`)
- Developer profile and information
- Animated text reveals
- Professional background
- Skills and expertise

### 3. Work Page (`work.html`)
- Portfolio showcase
- Project galleries
- Interactive project cards
- Case studies

### 4. Project Page (`project.html`)
- Individual project details
- Project walkthrough
- Technical specifications
- Live demos

### 5. Contact Page (`contact.html`)
- Contact form
- Social media links
- Location information
- Professional inquiries

## 🎭 Animation Features

### GSAP Animations
- **Scroll-triggered animations**: Elements animate as they enter the viewport
- **Text reveals**: Smooth text animations with various effects
- **Card movements**: Interactive card animations on scroll
- **Page transitions**: Smooth transitions between pages

### Lenis Smooth Scrolling
- **Buttery smooth scrolling**: Enhanced scrolling experience
- **Performance optimized**: Hardware-accelerated animations
- **Touch-friendly**: Works perfectly on mobile devices

## 🚀 Deployment

### Vercel Deployment (Recommended)

1. **Connect to Vercel**
   - Sign up/login to [Vercel](https://vercel.com)
   - Connect your GitHub repository

2. **Deploy automatically**
   - Vercel will automatically detect the Vite configuration
   - Build command: `npm run build`
   - Output directory: `dist`

3. **Custom domain** (optional)
   - Add your custom domain in Vercel dashboard
   - Configure DNS settings

### Manual Deployment

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Upload to your server**
   - Upload the `dist` folder contents to your web server
   - Ensure your server supports static file hosting

### Environment Variables

No environment variables are required for this project.

## 🔧 Configuration

### Vite Configuration (`vite.config.js`)
- Multi-page application setup
- Asset optimization
- Build optimization

### Vercel Configuration (`vercel.json`)
- Redirect rules for SPA routing
- Headers configuration
- Build settings

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Troubleshooting

### Common Issues

1. **Animations not working**
   - Ensure GSAP is properly loaded
   - Check browser console for errors
   - Verify scroll trigger setup

2. **Build errors**
   - Clear node_modules and reinstall: `rm -rf node_modules && npm install`
   - Check Node.js version compatibility

3. **Deployment issues**
   - Verify build output in `dist` folder
   - Check Vercel build logs
   - Ensure all assets are included

### Performance Optimization

- Images are optimized for web
- CSS and JS are minified in production
- Lazy loading for better performance
- Efficient animation techniques

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Codegrid** - Original template creators
- **GSAP** - Amazing animation library
- **Lenis** - Smooth scrolling library
- **Vite** - Fast build tool

## 📞 Contact

- **Portfolio**: [Juno Watts](https://your-deployment-url.com)
- **GitHub**: [@cosmocartier](https://github.com/cosmocartier)
- **Email**: your-email@example.com

---

**Made with ❤️ by Juno Watts | MWT July 2025 | Codegrid**

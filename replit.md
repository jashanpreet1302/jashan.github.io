# Jashanpreet Singh Sawhney - Portfolio Website

## Overview

This is a personal portfolio website for Jashanpreet Singh Sawhney, a C++ Developer Enthusiast passionate about ML/AI. The project is a static website built with vanilla HTML, CSS, and JavaScript, designed to showcase professional skills, projects, and contact information.

## System Architecture

The application follows a simple static website architecture:

- **Frontend Only**: Pure client-side application with no backend dependencies
- **Static File Serving**: Uses Python's built-in HTTP server for development
- **Responsive Design**: Mobile-first approach with responsive navigation and layouts
- **Modern Web Standards**: Utilizes modern CSS features like backdrop-filter and smooth scrolling

## Key Components

### Frontend Structure
- **HTML**: Semantic markup with proper meta tags for SEO
- **CSS**: Modern styling with CSS Grid and Flexbox layouts
- **JavaScript**: Vanilla JS for interactive features without framework dependencies
- **External Dependencies**: Google Fonts (Inter) and Font Awesome icons via CDN

### Core Features
1. **Responsive Navigation**: Mobile hamburger menu with smooth animations
2. **Smooth Scrolling**: Enhanced user experience with scroll-based navigation
3. **Active Section Highlighting**: Dynamic navigation state based on scroll position
4. **Contact Form**: Basic form structure (requires backend integration for functionality)
5. **Portfolio Sections**: Home, About, Portfolio, Contact, and Events sections

### File Organization
```
/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
├── .replit            # Replit configuration
└── attached_assets/   # Supporting assets and content
```

## Data Flow

The application operates entirely on the client-side:

1. **Page Load**: Static HTML loads with CSS and JavaScript assets
2. **Navigation**: JavaScript handles smooth scrolling and menu interactions
3. **Responsive Behavior**: CSS media queries adapt layout to different screen sizes
4. **User Interactions**: Event listeners manage navigation states and form interactions

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family for typography
- **Font Awesome**: Icon library for visual elements

### Development Tools
- **Python HTTP Server**: Simple static file serving for development
- **Replit Environment**: Cloud-based development and hosting platform

## Deployment Strategy

### Development Environment
- **Local Server**: Python 3.11 HTTP server on port 5000
- **Hot Reload**: Manual refresh required for changes
- **Cross-Platform**: Works on any system with Python support

### Production Considerations
The current setup is optimized for development. For production deployment, consider:
- Static hosting services (Netlify, Vercel, GitHub Pages)
- CDN integration for improved performance
- Asset optimization and minification
- SSL certificate for secure connections

### Replit Configuration
- **Modules**: Node.js 20 and Python 3.11 support
- **Workflow**: Automated server startup on port 5000
- **Deployment**: Simple shell command execution

## Changelog

Changelog:
- June 22, 2025. Initial setup

## User Preferences

Preferred communication style: Simple, everyday language.
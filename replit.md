# Modern Portfolio Website

## Overview

This is a modern, responsive single-page portfolio website designed for a CS student. The application is built using vanilla HTML, CSS, and JavaScript with no build process required. It features a clean, minimalist design with light/dark mode support, smooth animations, and comprehensive portfolio sections including hero, about, skills, projects, timeline, and contact.

## System Architecture

### Frontend Architecture
- **Static Site**: Pure HTML/CSS/JavaScript implementation without frameworks
- **Single Page Application (SPA)**: All content loads on a single page with smooth scrolling navigation
- **Component-based CSS**: Modular styling using CSS custom properties for theme management
- **Mobile-first Design**: Responsive layout that scales from mobile to desktop

### Theme System
- **CSS Custom Properties**: Centralized theme management using CSS variables
- **Dark/Light Mode**: Automatic OS detection with manual toggle capability
- **Theme Persistence**: Uses localStorage to remember user preference
- **WCAG Compliance**: Maintains contrast ratios ≥ 4.5:1 for accessibility

## Key Components

### Navigation System
- **Sticky Header**: Fixed navigation bar with smooth scroll to sections
- **Mobile Navigation**: Responsive hamburger menu for smaller screens
- **Theme Toggle**: Dark/light mode switcher integrated into navigation

### Content Sections
- **Hero Section**: Full-viewport introduction with call-to-action
- **About Section**: Personal bio and journey highlights
- **Skills Section**: Categorized technical abilities display
- **Projects Showcase**: Portfolio items with video thumbnails and website cards
- **Interactive Timeline**: Horizontal timeline spanning 2018-2025
- **Contact Form**: Validated contact form with user feedback

### Animation System
- **Scroll Animations**: Intersection Observer API for scroll-triggered effects
- **CSS Transitions**: Smooth hover effects and state changes
- **Loading Animations**: Progressive content reveal as user scrolls

## Data Flow

### Client-Side State Management
1. **Theme Preference**: Stored in localStorage, applied on page load
2. **Form Validation**: Real-time validation with error messaging
3. **Scroll Position**: Tracked for navigation highlighting and animations
4. **User Interactions**: Immediate feedback for buttons, links, and form elements

### Event Handling
- **Theme Toggle**: Updates CSS custom properties and localStorage
- **Form Submission**: Client-side validation before processing
- **Scroll Events**: Intersection Observer for performance-optimized animations
- **Navigation**: Smooth scroll behavior for section links

## External Dependencies

### Fonts
- **Google Fonts**: Inter font family (weights: 300, 400, 500, 600, 700)
- **Preconnect**: Optimized loading with DNS prefetch

### Icons
- **Feather Icons**: Lightweight icon library loaded via CDN
- **SVG Favicon**: Inline SVG for scalable favicon

### Browser APIs
- **Intersection Observer**: For scroll-triggered animations
- **localStorage**: Theme preference persistence
- **CSS Custom Properties**: Native CSS variable support

## Deployment Strategy

### Static Hosting
- **No Build Process**: Direct deployment of HTML/CSS/JS files
- **CDN Compatible**: All assets can be served from static hosting
- **Performance Optimized**: Minimal external dependencies, optimized loading

### Browser Support
- **Modern Browsers**: Requires CSS Custom Properties and Intersection Observer support
- **Progressive Enhancement**: Graceful degradation for older browsers
- **Mobile Responsive**: Works across all device sizes

### SEO Optimization
- **Meta Tags**: Proper title, description, and viewport tags
- **Semantic HTML**: Proper heading hierarchy and section structure
- **Accessibility**: ARIA labels, keyboard navigation, focus management

## Changelog

```
Changelog:
- June 27, 2025. Initial setup with modern portfolio website
- June 27, 2025. Updated color palette to bright/attractive themes
- June 27, 2025. Replaced "Your Name" with "Ganesh Mahapatra"
- June 27, 2025. Removed contact section completely
- June 27, 2025. Added photo placeholder on right side of about section
- June 27, 2025. Fixed JavaScript errors related to contact form
- June 27, 2025. Redesigned hero section with photo on right, text on left
- June 27, 2025. Updated hero text: "A Tech Enthusiast", CTA to "Know More"
- June 27, 2025. Changed "12th Grade Completed" to "Pursuing CS AI B.Tech"
- June 27, 2025. Updated skills sections: Web Dev (WordPress, HTML), AI Knowledge (Replit AI, Bolt AI, Lovable AI, Elementor)
- June 27, 2025. Updated Video Editing skills: Filmora, PowerDirector, Adobe Premiere Pro (Basics)
- June 27, 2025. Programming section: Python, HTML instead of Java
- June 27, 2025. Unified color palette to blue theme (#4F7FFF) for both light and dark modes
- June 27, 2025. Added user's profile photo to hero section
- June 27, 2025. Replaced profile photos with new user image (ganesh-photo.png)
- June 27, 2025. Removed timeline section completely from navigation and content
- June 27, 2025. Updated projects section to "Video Tutorials & Projects"
- June 27, 2025. Added YouTube video links: 3 tutorials with "Have a Look" buttons
- June 27, 2025. Added "Other Shorts" section for private content
- June 27, 2025. Changed "View Live" to "View" on website projects
- June 27, 2025. Modernized footer with 3-column layout: Navigation, Connect, Contact
- June 27, 2025. Added social media icons and modern footer styling
- June 27, 2025. Updated profile photo with new user image (ganesh-new-photo.png)
- June 27, 2025. Simplified footer to show only navigation links, removed Connect/Contact sections
- June 27, 2025. Removed heart icon from "Built with passion and dedication" text
- June 27, 2025. Fixed hero image positioning with rounded corners and better fitting
- June 27, 2025. Changed projects section title to "Projects and Work"
- June 27, 2025. Added custom YouTube thumbnails for all 3 tutorial videos
- June 27, 2025. Created unique parallelogram clip-path shape for hero image with rotation
- June 27, 2025. Updated portfolio website project to "Tech Updates Website" (GadgetGalaxyGuide)
- June 27, 2025. Added tech website thumbnail and "Still building it" status
- June 27, 2025. Removed "Another Website Project" card from projects section
- June 27, 2025. Updated project section subtitle to "Here are my some projects that I have build"
- June 27, 2025. Removed all transition delays for instant hover effects on skills and projects
- June 27, 2025. Added smooth 0.15s transitions for polished hover animations
- June 27, 2025. Fixed navigation to be sticky/fixed position to prevent scrolling issues
- June 27, 2025. Added hero section entry animations with fadeInUp effect (later removed)
- June 27, 2025. Optimized images with lazy loading attributes for faster page loads
- June 27, 2025. Added proper padding to hero section to account for fixed navigation
- June 27, 2025. Implemented sticky hero section that stays pinned when scrolling
- June 27, 2025. Removed hero animations for immediate content display
- June 27, 2025. Wrapped hero in container div with proper sticky positioning
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```
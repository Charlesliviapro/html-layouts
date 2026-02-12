# HTML Layout Planning Notes

## Overview
This project contains multiple HTML page layout skeletons demonstrating different common web page structures using semantic HTML5 elements.

## Layout Types

### 1. One-Column Layout (`one-column-layout.html`)
**Purpose**: Simple, focused content presentation ideal for blogs, articles, and mobile-first designs.

**Structure**:
- `<header>` - Site branding and navigation
- `<main>` - Primary content area
- `<footer>` - Copyright, links, contact info

**Use Cases**:
- Blog posts
- Article pages
- Mobile-responsive designs
- Simple landing pages

**Semantic Elements Used**: `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`

---

### 2. Two-Column Layout (`two-column-layout.html`)
**Purpose**: Combines main content with supplementary sidebar information.

**Structure**:
- `<header>` - Site header with navigation
- `<aside>` - Sidebar for supplementary content (navigation, widgets, ads)
- `<main>` - Primary content area
- `<footer>` - Site footer

**Use Cases**:
- Blog with sidebar
- Documentation sites
- E-commerce product pages
- News websites

**Semantic Elements Used**: `<header>`, `<nav>`, `<aside>`, `<main>`, `<article>`, `<section>`, `<footer>`

---

### 3. Landing Page Layout (`landing-page-layout.html`)
**Purpose**: Marketing-focused page designed for conversions and user engagement.

**Structure**:
- `<header>` - Logo and minimal navigation
- `<section class="hero">` - Hero section with main value proposition
- `<section class="features">` - Features or benefits section
- `<section class="testimonials">` - Social proof or testimonials
- `<section class="cta">` - Call-to-action section
- `<footer>` - Footer with links and contact

**Use Cases**:
- Product launches
- Marketing campaigns
- SaaS homepages
- Event registrations

**Semantic Elements Used**: `<header>`, `<nav>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<footer>`

---

### 4. Fixed Header Layout (`fixed-header-layout.html`)
**Purpose**: Persistent navigation header that remains visible while scrolling.

**Structure**:
- `<header>` (fixed position) - Always-visible navigation
- `<main>` - Scrollable content area with proper top padding
- `<footer>` - Bottom content

**Use Cases**:
- Long-form content sites
- Web applications
- Documentation
- Any site requiring constant navigation access

**Semantic Elements Used**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`

---

## Semantic HTML5 Elements Reference

### Structural Elements
- `<header>` - Introductory content or navigation
- `<nav>` - Navigation links
- `<main>` - Main content (only one per page)
- `<section>` - Thematic grouping of content
- `<article>` - Self-contained, independently distributable content
- `<aside>` - Tangentially related content (sidebars, callouts)
- `<footer>` - Footer information

### Content Elements
- `<figure>` - Self-contained content (images, diagrams, code)
- `<figcaption>` - Caption for figure element
- `<time>` - Date/time information
- `<address>` - Contact information

## Design Principles

1. **Semantic HTML First**: Use HTML elements that describe the content's meaning, not just its appearance
2. **Accessibility**: Proper semantic structure improves screen reader navigation
3. **SEO Benefits**: Search engines better understand semantically structured content
4. **Maintainability**: Clear structure makes code easier to understand and modify
5. **Responsive Design**: Layouts should adapt to different screen sizes (demonstrated with CSS)

## CSS Strategy

Each layout includes basic CSS to:
- Demonstrate the layout structure visually
- Show positioning relationships between elements
- Provide a starting point for customization
- Maintain responsiveness across devices

## Browser Compatibility

All semantic HTML5 elements used are supported in:
- Chrome 26+
- Firefox 21+
- Safari 7+
- Edge 12+
- Opera 15+

## Future Enhancements

Potential additions to this project:
- Three-column layout
- Grid-based layouts
- Card-based layouts
- Dashboard layout
- Magazine-style layout
- Responsive navigation patterns

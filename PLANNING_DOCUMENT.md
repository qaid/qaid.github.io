# qaidjacobs.com GitHub Pages Migration Plan

## Project Overview
Replace the current Squarespace-hosted qaidjacobs.com with an equally capable static website that can be published for free using GitHub Pages.

## Current Website Analysis

### Site Structure
The current website has a clean, professional portfolio structure with 5 main sections:

1. **Home (/)** - Landing page with hero section, services overview, and featured projects
2. **Work (/work)** - Portfolio showcase with case study previews
3. **About (/about)** - Personal background and professional timeline
4. **Publicly (/publicly)** - Speaking engagements, podcast appearances, presentations
5. **Contact (/contact)** - Contact form and social media links

### Key Features to Replicate

#### Navigation & Layout
- [ ] Responsive navigation menu (mobile hamburger menu)
- [ ] Clean, modern design aesthetic
- [ ] Professional typography and spacing
- [ ] Mobile-first responsive design
- [ ] Consistent header/footer across all pages

#### Content Management
- [ ] Hero sections with personal branding
- [ ] Project case studies with detailed breakdowns
- [ ] Professional timeline/resume format
- [ ] Media gallery for speaking engagements
- [ ] Rich media content support (images, embedded videos)

#### Technical Features
- [ ] Contact form functionality
- [ ] SEO optimization (meta tags, structured data)
- [ ] Image optimization and responsive images
- [ ] Clean URLs and navigation
- [ ] Fast loading performance
- [ ] Accessibility compliance

## Technical Implementation Plan

### Phase 1: Foundation Setup
- [ ] Create GitHub repository for the new site
- [ ] Choose static site generator (Jekyll, Hugo, or custom HTML/CSS/JS)
- [ ] Set up local development environment
- [ ] Configure GitHub Pages deployment workflow

### Phase 2: Core Structure
- [ ] Build responsive layout framework
- [ ] Implement navigation system
- [ ] Create page templates for each section
- [ ] Set up CSS/SCSS architecture
- [ ] Implement mobile-responsive design

### Phase 3: Content Migration
- [ ] **Home Page**
  - Hero section with introduction
  - Services overview (Creative Direction, UX/Product Design, Design Mentorship)
  - Featured projects section
  - Call-to-action sections
  
- [ ] **Work Page**
  - Portfolio grid layout
  - Case study preview cards
  - Skills profiling section
  - Individual case study pages:
    - The Wild Bookstore
    - Amplifon Audiologist Dashboard
    - The Usual Hotel User Experience

- [ ] **About Page**
  - Personal introduction section
  - Career journey narrative
  - Professional experience timeline
  - Contact call-to-action

- [ ] **Publicly Page**
  - Speaking engagements list
  - Podcast appearances
  - Presentation videos/links
  - Media gallery layout

- [ ] **Contact Page**
  - Contact form (using Netlify Forms or Formspree)
  - Social media links
  - Professional contact information

### Phase 4: Advanced Features
- [ ] Contact form integration (Netlify Forms, Formspree, or EmailJS)
- [ ] Image optimization and lazy loading
- [ ] SEO implementation (meta tags, Open Graph, structured data)
- [ ] Performance optimization
- [ ] Analytics integration (Google Analytics)

### Phase 5: Content Enhancement
- [ ] Gather and optimize all images from current site
- [ ] Migrate all case study content with proper formatting
- [ ] Ensure all external links are working
- [ ] Add any missing content or updates

### Phase 6: Testing & Deployment
- [ ] Cross-browser testing
- [ ] Mobile responsiveness testing
- [ ] Performance testing (PageSpeed Insights)
- [ ] Accessibility testing
- [ ] SEO validation
- [ ] Deploy to GitHub Pages
- [ ] Configure custom domain (qaidjacobs.com)

## Technology Stack Recommendations

### Option 1: Jekyll (GitHub Pages Native)
**Pros:**
- Native GitHub Pages support
- Ruby-based, mature ecosystem
- Built-in blog functionality
- Liquid templating
- Large community

**Cons:**
- Ruby dependency
- Slower build times
- Learning curve for Liquid

### Option 2: Hugo (Fast Static Site Generator)
**Pros:**
- Extremely fast build times
- Go-based, single binary
- Powerful templating
- Great performance
- Modern workflow

**Cons:**
- Requires GitHub Actions for deployment
- Go templating learning curve

### Option 3: Custom HTML/CSS/JS
**Pros:**
- Complete control
- No build process complexity
- Direct GitHub Pages compatibility
- Lightweight

**Cons:**
- More manual work
- No templating benefits
- Harder to maintain

## Recommended Approach: Jekyll

Jekyll is recommended because:
1. Native GitHub Pages support (no custom deployment needed)
2. Perfect for portfolio sites
3. Good templating system for reusable components
4. Strong SEO capabilities
5. Large community and documentation

## File Structure Plan
```
qaidjacobs.com/
├── _config.yml
├── _layouts/
│   ├── default.html
│   ├── page.html
│   └── case-study.html
├── _includes/
│   ├── header.html
│   ├── footer.html
│   └── navigation.html
├── _sass/
│   ├── _base.scss
│   ├── _layout.scss
│   └── _components.scss
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── _work/
│   ├── the-wild.md
│   ├── amplifon.md
│   └── the-usual-hotel.md
├── index.html
├── work.html
├── about.html
├── publicly.html
├── contact.html
└── README.md
```

## Success Criteria
- [ ] Site loads in under 3 seconds
- [ ] Mobile responsiveness across all devices
- [ ] All original content successfully migrated
- [ ] Contact form functional
- [ ] SEO performance maintained or improved
- [ ] Accessibility compliance (WCAG 2.1 AA)
- [ ] Custom domain properly configured
- [ ] All case studies properly formatted and readable

## Timeline Estimate
- **Phase 1-2 (Foundation & Structure):** 2-3 days
- **Phase 3 (Content Migration):** 3-4 days
- **Phase 4 (Advanced Features):** 2-3 days
- **Phase 5 (Content Enhancement):** 1-2 days
- **Phase 6 (Testing & Deployment):** 1-2 days

**Total Estimated Time:** 9-14 days

## Next Steps
1. Confirm technology choice (Jekyll recommended)
2. Set up GitHub repository
3. Begin with Phase 1: Foundation Setup
4. Create basic Jekyll site structure
5. Start building responsive layout framework

---

*This document will be updated as the project progresses and requirements are refined.*

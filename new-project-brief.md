# New Project Brief & Roadmap

This brief is designed to be a comprehensive, repeatable framework for building a premium, highly-animated, and SEO-optimized web experience from scratch for any new client. It ensures we end up with the same high-quality end result—Astro + Tailwind CSS setup, GSAP animations, perfect responsiveness, and deep local SEO—while adding a robust Discovery Phase to align with the new brand perfectly.

---

## Phase 1: Discovery & Requirements Gathering
*The goal of this phase is to extract all necessary information from the client before any design or code begins.*

- [ ] **Client Questionnaire:**
  - Company Legal Name & Trading Name
  - Primary Contact Information (Phone, Email, Physical Address)
  - Core Services Provided
  - Target Audience / Customer Demographics
  - Unique Selling Propositions (What makes them better than competitors?)
  - Service Areas (Specific towns, cities, or regions covered for Local SEO)
- [ ] **Brand Alignment:**
  - Existing Brand Assets (Logos, Brand Guidelines, existing color codes)
  - Tone of Voice (e.g., Professional, Friendly, Authoritative, Playful)
  - 3-5 reference websites they admire (and what they like about them)
- [ ] **Technical Requirements:**
  - Domain Name status (Do they own it? Who hosts it?)
  - Required integrations (e.g., Booking systems, contact forms, social media feeds)

## Phase 2: Design & Brand Foundation
*Translating discovery insights into a visual language.*

- [ ] Agree on Site Structure & Sitemap (e.g., Home, About, Services, Contact)
- [ ] Select Typography (Pairing Headings & Body fonts)
- [ ] Lock in Color Palette (Primary, Secondary, Accent, Background, Text)
- [ ] Review & integrate logo into a responsive header layout
- [ ] Wireframe critical sections (Hero, Services Grid, Call to Action)

## Phase 3: Technical Setup & Architecture
*Building the modern, lightning-fast foundation.*

- [ ] Initialize Astro project for static site generation
- [ ] Integrate Tailwind CSS for utility-first styling
- [ ] Initialize Git repository and set up remote hosting (GitHub)
- [ ] Set up global layout wrappers and reusable UI components (Buttons, Cards, Modals)
- [ ] Configure base styles, CSS variables, and Tailwind theme configuration

## Phase 4: Core Static Build (Desktop-First)
*Building the semantic structure of the site without worrying about mobile or animations yet.*

- [ ] Structure semantic HTML boilerplate
- [ ] Build Hero Section (Impactful headline, CTA, hero visual)
- [ ] Build Main Content Sections (Services grid, "Why Choose Us", Reviews/Testimonials, About snippet)
- [ ] Build Footer (Links, contact info, service areas)
- [ ] Build Desktop Navigation (Logo, links, primary CTA)

## Phase 5: Responsive Design & Mobile Experience
*Ensuring the site looks perfect on every device.*

- [ ] Adapt layout constraints and typography for Tablet screens
- [ ] Adapt layout and stacking order for Mobile screens
- [ ] Build custom Responsive Mobile Navigation (Burger menu, slide/fade-in overlay, trap focus)
- [ ] Test tap targets and interactive elements for mobile usability

## Phase 6: SEO & Digital Assets
*Optimizing the site for search engines and social sharing.*

- [ ] Generate & implement Favicon and Apple Touch/App Icons
- [ ] Add Global SEO Meta tags (Title, Description, Keywords)
- [ ] Add Open Graph (OG) & Twitter card data for dynamic social sharing previews
- [ ] Include Web App Manifest for PWA support
- [ ] Obfuscate contact details (phone/email) to protect against scrapers
- [ ] **Local SEO Implementation:**
  - Weave specific location keywords into headings and body copy
  - Implement Local Business structured data (Schema.org JSON-LD)
  - Optimize "Areas We Serve" content in footer/navigation

## Phase 7: GSAP Animations & Micro-Interactions
*Bringing the site to life with premium, performant animations.*

- [ ] Install and configure GSAP (GreenSock) and ScrollTrigger
- [ ] Implement Scroll Reveals (staggered fade-ins, slide-ups as elements enter the viewport)
- [ ] Add complex visual interactions (e.g., overlapping elements, parallax, scrolling carousels)
- [ ] Refine Hover States on links, buttons, and cards
- [ ] Add smooth page load transitions / entry animations
- [ ] Ensure mobile fallbacks and verify animations pause/respect "prefers-reduced-motion"

## Phase 8: Testing & Quality Assurance
*Polishing the final product before revealing it to the world.*

- [ ] Perform cross-browser testing (Chrome, Safari, Firefox)
- [ ] Perform cross-device testing (iOS, Android, macOS, Windows)
- [ ] Run Lighthouse Audits for Performance, Accessibility, Best Practices, and SEO (Aiming for 95+)
- [ ] Verify all links, buttons, and form submissions

## Phase 9: Deployment & Handover
*Going live and setting up the client for success.*

- [ ] Final commit & push to GitHub
- [ ] Deploy live site via Vercel (or preferred hosting platform)
- [ ] Connect and configure custom domain with SSL
- [ ] Ensure 301 Redirects are in place if replacing an old website

## Phase 10: Compliance & Analytics
*Post-launch monitoring and legal requirements.*

- [ ] Add Cookie consent banner (if legally required for the target region)
- [ ] Integrate Google Analytics / Plausible / Fathom for traffic monitoring
- [ ] Provide client with instructions on setting up or optimizing their Google Business Profile

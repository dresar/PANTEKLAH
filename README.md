# Ovix — Creative Digital Agency & Portfolio HTML Template

**Ovix** is a premium, modern, and fully responsive HTML5 creative agency and portfolio template. It is designed for digital agencies, freelancer portfolios, developer directories, start-ups, and designers looking to present their work with high-end aesthetic appeal. 

---

## 🌟 Key Features

- **Multiple Homepage Layouts**:
  - 🌐 **Web Design Agency** (`index.html`) — Focused on agency branding and creative services.
  - 💻 **Find Developers** (`home-2.html`) — Optimized for software teams and developer directories.
  - 🎨 **Personal Portfolio** (`home-3.html`) — Tailored for creative individuals and designers.
- **Full E-Commerce Flow**: Shop pages (`shop.html`, `shop-single.html`), Cart (`cart.html`), and Checkout (`checkout.html`) templates included.
- **Portfolio & Project Case Studies**: Multi-style projects gallery (`project.html`) and dedicated details page (`project-single.html`).
- **Comprehensive Inside Pages**: About page, Team lists, Careers/Job board, FAQs, and fully featured News/Blog system.
- **Premium User Experience**: Embedded with micro-animations, smooth scrolling, and page reveal effects.

---

## 🖼️ CDN Image Integration & Performance

To optimize page loading times and streamline developer deployment, **all photographic assets on the website have been integrated with high-performance CDNs**:

1. **Primary Portfolio Featured Image**:
   - URL: `https://res.cloudinary.com/dpgybasuh/image/upload/v1782790021/portfolio/frud9oq4hunutdol4apr.jpg`
   - Used in: Hero banners, main about images, prominent portfolio features, and portfolio details.
2. **Curated Unsplash CDN Collection**:
   - Used for team portraits, client testimonial avatars, shop products, and news/blog images.
   - Handpicked, high-definition imagery that ensures each page looks authentic and premium.
3. **Local Vector & UI Assets**:
   - Branding logos (`logo.svg`), system icons (`category.svg`, `arrow-up.svg`), and decorative background vectors remain locally hosted under `assets/img/` to preserve website structural layout integrity.

---

## 📂 Project Structure

```text
├── assets/
│   ├── css/          # Core styling files (bootstrap, fontawesome, main.css, rs6.css, etc.)
│   ├── fonts/        # Web fonts & FontAwesome assets
│   ├── img/          # Local vector logo & UI icons (SVGs and layout-critical shapes)
│   ├── js/           # Interactive components (bootstrap.bundle, swiper, odometer, main.js)
│   └── scss/         # SCSS source files for style customization
├── about.html        # Agency story & background page
├── blog.html         # News & articles list
├── blog-single.html  # Single article details page
├── career.html       # Job opportunities list
├── career-single.html# Job description & details page
├── cart.html         # E-commerce shopping cart
├── checkout.html     # E-commerce checkout form
├── contact.html      # Contact form & location page
├── faq.html          # Interactive accordion questions
├── index.html        # Web Design Agency (Default Home)
├── home-2.html       # Find Developers (Home Alternate)
├── home-3.html       # Personal Portfolio (Home Alternate)
├── project.html      # Portfolio gallery
├── project-single.html# Portfolio details page
├── service.html      # Services list
├── service-single.html# Service description details page
├── shop.html         # Product list page
├── shop-single.html  # Single product preview page
├── team.html         # Agency members showcase page
├── team-single.html  # Member background profile page
└── README.md         # Documentation file
```

---

## 🛠️ Technology Stack

- **Markup**: HTML5
- **Style**: CSS3 & SCSS (pre-configured)
- **Framework**: Bootstrap v5.x
- **Icons**: FontAwesome Pro & Custom SVGs
- **Sliders & Swipers**: Swiper.js
- **Animations**: Animate.css, Odometer.js, and Custom Scroll Reveal effects
- **Libraries**: jQuery

---

## 🚀 Getting Started & Local Running

Since this is a static HTML template, no build process is required for basic local testing:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dresar/PANTEKLAH.git
   cd PANTEKLAH
   ```
2. **Launch a Local Server**:
   You can open any `.html` file directly in your browser. However, for features like page transitions or sticky navigations to load optimally, running a local dev server is recommended:
   - **Using VS Code Live Server extension**: Right-click `index.html` and click *Open with Live Server*.
   - **Using Node.js**:
     ```bash
     npx http-server ./
     ```
   - **Using Python**:
     ```bash
     python -m http.server 8000
     ```

---

## 🌐 Deployment Instructions

### GitHub Pages (Recommended)
1. Commit and push your code to your GitHub repository.
2. In the repository settings, go to the **Pages** tab.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` or `master` branch and the folder `/ (root)`.
5. Click **Save**. Your site will be live within a few minutes!

### Netlify / Vercel
1. Connect your GitHub account to Netlify or Vercel.
2. Select the `PANTEKLAH` repository.
3. Leave the build commands and output directory blank (the platforms automatically detect static assets).
4. Click **Deploy**.

---

*Ovix Template - Developed for digital agencies, personal portfolios, and web design shops.*
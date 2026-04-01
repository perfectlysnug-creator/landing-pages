# Perfectly Snug Landing Page v2

High-converting landing page designed to outperform the current homepage for ad traffic conversion.

## 🚀 Quick Setup

### Enable GitHub Pages (Manual)
1. Go to: https://github.com/perfectlysnug-creator/landing-pages/settings/pages
2. Under "Source", select "Deploy from a branch"
3. Choose "main" branch and "/ (root)" folder
4. Click Save

The site will be live at: **https://perfectlysnug-creator.github.io/landing-pages/**

### Local Development
```bash
# Serve locally (requires Python)
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

## 📊 Features

- **Premium Design**: Dark/light alternating sections with Perfectly Snug brand colors
- **Mobile-First**: Fully responsive, optimized for mobile traffic
- **Performance**: Compressed assets, lazy loading, smooth animations
- **Conversion Optimized**: Every section drives toward the CTA
- **Interactive**: Testimonials slider, FAQ accordion, smooth scroll
- **Clinical Data**: SleepSpace study results prominently featured
- **Social Proof**: Press logos, testimonials, expert endorsement

## 🎨 Brand Specs

- **Headings**: Playfair Display (serif)
- **Body**: Montserrat (sans-serif)
- **Dark Blue**: #25343E
- **Light Blue**: #E0F0F2  
- **Yellow**: #F2D980
- **Grey Text**: #667085

## 📝 Content Sections

1. Sticky Promo Bar (easy to update)
2. Navigation with CTA
3. Hero with video background
4. Trust badges (shipping, warranty, trial)
5. Press logos ("As Seen In")
6. How It Works (3 steps)
7. The Problem (temperature issues)
8. The Solution (key features)
9. Clinical Results (SleepSpace study)
10. Customer Testimonials (5 reviews, auto-rotating)
11. Expert Endorsement (Dr. Casey)
12. Competitor Comparison Table
13. Risk Reversal (guarantees)
14. FAQ (8 questions, accordion)
15. Final CTA with trust reminders
16. Footer

## 🔧 Customization

### Update Promo Code
Edit line 364 in `index.html`:
```html
<!-- PROMO: Change offer text here -->
<div class="promo-bar">
    EASTER26 — Save Up to $270 | Free Shipping
</div>
```

### Technical Notes
- All testimonials used exactly as provided (including typos per instructions)
- Large files compressed: hero image (291KB), video (3.8MB)
- Excluded from repo: Original 6.3MB hero image, 13MB videos
- Uses Shopify CDN video URL for setup demo
- Smooth scroll, intersection observers for animations
- FAQ accordion with vanilla JavaScript

## 🎯 Conversion Elements

- **Urgency**: Promo code with savings amount
- **Trust**: 30-day trial, warranty, free shipping
- **Social Proof**: 4.87/5 stars, clinical study, testimonials
- **Authority**: Dr. Casey endorsement, press coverage
- **Scarcity**: Clinical results, comparison advantages
- **Risk Reversal**: Money-back guarantee, free returns

Built for Amanda McLaughlin / Matty Marketing
Client: Perfectly Snug Smart Topper
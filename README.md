# Saceatry Jewellers

**Premium Rose Gold Jewellery Since 1995**

Official website for Saceatry Jewellers — a professional, modern, and fully responsive jewellery showcase website with WhatsApp-based enquiry system.

## Live Website

Once GitHub Pages is enabled, the site will be available at:
**https://rahul-mech.github.io/saceatry-jewellers/**

## Features

- Clean & Luxury Design (Rose Gold theme)
- Fully Responsive (Mobile + Desktop)
- Sticky Header + Smooth Navigation
- Shop by Category section
- Featured Products with WhatsApp Enquiry
- Pre-filled WhatsApp messages with product details
- Floating WhatsApp button
- Since 1995 branding
- Contact section with Phone, Mobile & Email
- Professional Footer

## Contact Details

- **Mobile**: +91 98134 23710
- **Telephone**: 1600347292
- **Email**: saceatry_jwellers@gmail.com

## How to Enable GitHub Pages

1. Go to repository **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main` and folder: `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes and your site will be live

## Adding New Products

Open `index.html` and find the `products` array inside the `<script>` tag at the bottom. Simply add a new object:

```js
{
    id: 'RG-R-003',
    name: 'New Ring Name',
    category: 'Rings',
    weight: '3.5g',
    price: 'Price on Request',
    description: 'Short description here.'
}
```

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Google Fonts (Playfair Display + Inter)

---

Built with ❤️ for Saceatry Jewellers
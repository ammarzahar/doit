# Doit Landing Page

A modern, animated landing page for Doit Tech Agency.

## Recent Updates

### ✅ Email Integration (Latest)
- **Direct Email Sending**: Contact form now sends emails directly to `jootawanhq@gmail.com` using EmailJS
- **No Email Client Required**: Users don't need to open their email app anymore
- **Loading State**: Submit button shows "Sending..." animation while processing
- **Error Handling**: Displays user-friendly error messages if sending fails

### ✅ Modal Fix
- **Close Button Working**: The 'x' button on the promo popup now functions correctly
- **Better UX**: Added hover effects and proper click area for the close button
- **Event Handling**: Fixed event propagation to prevent backdrop clicks from interfering

## Setup Instructions

### 1. EmailJS Configuration (Required for Contact Form)

The contact form requires EmailJS to be configured. Follow these steps:

1. Read the detailed setup guide: `EMAILJS_SETUP.md` (in the artifacts folder)
2. Create a free EmailJS account at https://www.emailjs.com/
3. Get your Service ID, Template ID, and Public Key
4. Update `index.html` with your credentials:
   - Line ~21: Replace `YOUR_PUBLIC_KEY`
   - Line ~795: Replace `YOUR_SERVICE_ID` and `YOUR_TEMPLATE_ID`

**Note**: Without EmailJS configuration, the form will show an error. The setup is free for up to 200 emails/month.

### 2. Running Locally

Simply open `index.html` in your browser. No build process required!

## Features

- 🎨 Modern glassmorphism design
- 🌊 Animated 3D particle background (Three.js)
- 🎠 3D rotating client carousel
- 📱 Fully responsive
- ✉️ Direct email integration
- 🎯 Interactive service selection
- 🎉 Year-end sales promo popup
- ⚡ Smooth animations (GSAP)

## Tech Stack

- HTML5
- TailwindCSS (CDN)
- Three.js (3D animations)
- GSAP (Scroll animations)
- EmailJS (Email sending)
- Font Awesome (Icons)

## File Structure

```
doitlandingpage/
├── index.html          # Main landing page
├── images/            # Logo and image assets
│   ├── Doit New Logo_White BG.svg
│   └── aisy-asyraf.svg
├── README.md          # This file
└── .env.example       # EmailJS config template
```

## Contact

For questions or support, email: jootawanhq@gmail.com

---

© 2023 Doit Tech Agency. All rights reserved.

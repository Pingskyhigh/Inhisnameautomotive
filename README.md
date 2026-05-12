# In His Name Automotive Website

A professional website for an automotive repair shop featuring appointment requests and customer testimonials.

## Pages

- **Home (index.html)** - Introduction to the business, services offered, and call-to-action buttons
- **Appointment Request (appointment.html)** - Form for customers to request appointments
- **Testimonials (testimonials.html)** - Display of customer reviews and ratings

## Features

✅ Responsive design (works on desktop, tablet, and mobile)
✅ Professional styling with brand colors
✅ Appointment request form
✅ Customer testimonials grid
✅ Navigation menu across all pages
✅ Call-to-action buttons throughout the site

## Setup Instructions

### 1. Connect the Appointment Form (Important!)

The appointment form currently uses Formspree for email submissions. You need to:

1. Go to [Formspree.io](https://formspree.io) and sign up (free)
2. Create a new form and get your Form ID
3. In `appointment.html`, replace `YOUR_FORM_ID` in this line:
   ```html
   <form class="appointment-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
   with your actual Formspree ID.

**Example:** If your Formspree ID is `xyzabc123`, it should look like:
```html
<form class="appointment-form" action="https://formspree.io/f/xyzabc123" method="POST">
```

### 2. Update Contact Information

In `appointment.html`, update the contact info section with your actual business details:
- Phone number
- Operating hours

### 3. Customize Content

- Edit testimonials in `testimonials.html` to match your actual customer reviews
- Update business name references if needed
- Add or remove services from the services list on the home page

## Files Structure

```
Inhisnameautomotive/
├── index.html           # Home page
├── appointment.html     # Appointment request page
├── testimonials.html    # Customer testimonials page
├── style.css           # All styling
└── README.md           # This file
```

## Deployment Options

### Option 1: GitHub Pages (Free & Easy)
1. Go to your repository Settings
2. Scroll to "Pages" section
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Click Save
6. Your site will be live at: `https://Pingskyhigh.github.io/Inhisnameautomotive`

### Option 2: Other Hosting
You can also host this on:
- Netlify (free tier available)
- Vercel
- Any web hosting service that supports static sites

## Customization Tips

### Colors
Edit the color variables in `style.css`:
```css
:root {
    --primary-color: #1a3a52;      /* Dark blue */
    --secondary-color: #d32f2f;    /* Red accent */
    --accent-color: #f5f5f5;       /* Light gray background */
}
```

### Fonts
Change the font-family in `style.css` under the `body` selector

### Adding More Testimonials
Copy a `testimonial-card` div in `testimonials.html` and modify the text and author name

## Support

For questions or help with customization, reach out!

---

Built with care for your automotive business. 🚗
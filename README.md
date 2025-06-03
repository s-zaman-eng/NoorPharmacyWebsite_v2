# Noor Pharmacy Website

A professional static website for Noor Pharmacy located in Jackson Heights, NY. This website provides information about pharmaceutical services, contact details, and business hours.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Service Information**: Detailed information about pharmacy services including:
  - Free pickup & delivery
  - Insurance acceptance (all major plans)
  - OTC medications
  - Phone & utility bill payments
  - Money transfer services
- **Contact Information**: Complete contact details with Google Maps integration
- **Professional Branding**: Custom green theme matching pharmacy branding
- **Interactive Elements**: Contact forms, navigation, and map functionality

## Services Offered

- Prescription medications
- Over-the-counter medications
- Free pickup and delivery
- Insurance processing (all major insurances accepted)
- Phone and utility bill payments
- Money transfer services
- Medication consultation
- Business services (notary, copying, fax)

## Contact Information

**Address:** 3703 74th Street, Jackson Heights, NY 11372  
**Phone:** 347-396-5303  
**Email:** noorpharmacynyc@gmail.com

## Technologies Used

- HTML5
- CSS3 (Custom styling with CSS variables)
- JavaScript (Vanilla JS)
- Bootstrap 5.3.0
- Font Awesome 6.4.0
- Google Fonts (Inter)

## File Structure

```
├── index.html          # Homepage
├── about.html          # About us page
├── services.html       # Services page
├── contact.html        # Contact page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
├── assets/
│   ├── logo.svg        # Pharmacy logo
│   └── wallpaperflare.com_wallpaper.jpg  # Background image
├── favicon.svg         # Website favicon
└── favicon.ico         # Fallback favicon
```

## Setup Instructions

1. Clone or download this repository
2. Open `index.html` in a web browser
3. For Google Maps functionality, add your Google Maps API key in `contact.html`

## Deployment

This is a static website that can be deployed on:
- GitHub Pages
- Netlify
- Vercel
- Any web hosting service

### GitHub Pages Deployment

1. Fork or upload this repository to GitHub
2. Go to repository Settings
3. Navigate to Pages section
4. Select source branch (usually `main` or `master`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

## Customization

### Colors
The website uses CSS variables for easy color customization. Edit the `:root` section in `css/style.css`:

```css
:root {
    --primary-color: 122 39% 49%;    /* Main green color */
    --primary-dark: 122 53% 23%;     /* Darker green */
    --primary-light: 122 39% 78%;    /* Lighter green */
}
```

### Content
- Update contact information in all HTML files
- Replace logo in `assets/logo.svg`
- Modify services in `services.html`
- Update business hours in `contact.html`

### Google Maps
To enable the interactive map:
1. Get a Google Maps API key from Google Cloud Console
2. Replace `YOUR_API_KEY` in `contact.html` with your actual API key

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This website is created for Noor Pharmacy. All rights reserved.

## Support

For technical support or modifications, please contact the development team.
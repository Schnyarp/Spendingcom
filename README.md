# spending.com – Domain For Sale Landing Page

This repository contains the code for the [spending.com](https://spending.com) domain-for-sale landing page.

## Purpose

The site is a single-page landing page designed to inform visitors that spending.com is for sale, highlight its value, and collect purchase inquiries via the contact form.

## Features

- Clean, mobile-friendly design
- Automatically displays the current domain in the browser bar and form submissions
- Inquiry form submits via email using mailto links
- Fast, static HTML+CSS+JS for easy deployment anywhere
- Easily adapted for other domains

## Usage

1. **Clone or download this repository.**
2. **Edit the site content** (domain name, form endpoint, features, etc.) as needed in `index.html`.
3. **Deploy to your preferred static host** (Netlify, Vercel, GitHub Pages, cPanel, etc.).
4. **Configure your DNS** so spending.com points to your hosting provider.

## Customization

- Update the domain name in the header (`index.html`) and any references in the code.
- Change the email endpoint if you wish to receive inquiries at a different address.
- Adjust styles or features as needed.

## DNS Setup

For best results, use a CNAME (for subdomains) or ALIAS/ANAME or A record (for root domains) to point spending.com to your host.  
Do **not** use HTTP redirects—this will break domain detection and form tracking.

## License

This landing page is provided as-is for use with your domain sales. No warranties.  
Feel free to modify for your own domains.

---

**Questions or need help?**  
Contact the domain owner via the inquiry form on the landing page.

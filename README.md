# Polymer Shop Clone

This is a mobile-first, responsive clone of the Polymer Shop website. The project simulates a basic e-commerce flow with the following pages:
- Home
- Item Listing
- Single Item Details
- Cart (with hardcoded items)
- Checkout (form data is not sent)

## Features
- **Mobile-first approach:** The website is fully responsive and designed for an optimal experience on mobile devices.
- **Product listing:** Displays various products available for purchase.
- **Cart functionality:** Shows hardcoded items in the cart.
- **Checkout page:** Allows users to input details for account information, shipping address, billing address, and payment method (form data is not sent).
- **Navigation:** Simple navigation between pages using links.

## Pages

1. **Home**: Displays the main homepage with a link to the product listings.
2. **Item Listing**: Shows a list of available products.
3. **Single Item**: Displays detailed information about a specific product.
4. **Cart**: Displays a summary of selected items with total pricing.
5. **Checkout**: Allows users to input their account, shipping, and payment details. The form is purely for demonstration purposes.

## Mobile-first design
- The website is developed using CSS Flexbox for layout management.
- Media queries are used to adjust the layout for larger screens.
- The design focuses on responsiveness, with dynamic sizing using percentages for optimal viewing on various devices.

## Technologies used

- **HTML5**: Markup language for structuring the content of the website.
- **CSS3**: For styling the layout, including a mobile-first design using Flexbox and media queries.
- **Google Fonts**: Utilized for custom fonts.
- **Material Icons**: Used for icons like the menu and cart.

## Project Structure

```
/project-root
│
├── /css
│   └── cart.css
│   └── checkout.css
│   └── index.css
│   └── item-detail.css
│   └── item-listing.css
├── /img
│   └── (images for products, cart icon, etc.)
├── .gitignore
├── cart.html
├── checkout.html
├── index.html (Home Page)
├── item-detail.html
├── item-listing.html
├── README.md (This file)
├── remains.txt
└── styles.css
```

## .gitignore

The `.gitignore` file includes:
- The `node_modules/` folder (if applicable)
- The `dist/` folder for any build outputs
- Any temporary files like `.DS_Store`, `*.log`, etc.


  
---
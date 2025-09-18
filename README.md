# Twilight Clothing Store

A modern, responsive e-commerce website for Twilight Clothing Store, managed by Natalie.

**Live Website URL:** https://keli281.github.io/multipage-website/

## Project Purpose

Twilight Clothing Store is a responsive multipage e-commerce website showcasing Natalie's clothing collection. The website serves as an online presence for the boutique, allowing customers to browse products, learn about the brand, and contact the store.

## Planning Process

### Website Structure
- **Homepage:** Introduces the brand with a hero section, featured products, and newsletter signup
- **Products:** Filterable product gallery with category filtering functionality
- **About:** Company story, values, and brand philosophy
- **Contact:** Contact form with validation and store information

### Design Choices
- **Color scheme:** Dark blue (#0d1b2a, #1b263b) and pink (#e83e8c) for dark mode, white and pink for light mode
- **Typography:** Clean, modern sans-serif fonts for readability
- **Layout:** Responsive design using CSS Grid and Flexbox
- **Interactive elements:** Theme toggle, product filtering, form validation
- **User experience:** Intuitive navigation with clear visual hierarchy

## Technical Implementation

### Technologies Used
- **HTML5** with semantic markup for accessibility and SEO
- **CSS3** with Flexbox/Grid for responsive layouts
- **JavaScript** for interactive elements and dynamic functionality
- **GitHub Pages** for deployment and hosting

### Key Features
1. **Responsive Design:** Fully responsive across mobile, tablet, and desktop devices
2. **Dark/Light Mode:** Theme toggle with persistent user preference using localStorage
3. **Product Filtering:** JavaScript-powered category filtering system
4. **Form Validation:** Client-side validation for contact form and newsletter signup
5. **Smooth Navigation:** Responsive navigation with active state indicators

### Challenges and Solutions
- **Challenge:** Implementing theme persistence across pages
  **Solution:** Used localStorage to save user's theme preference and applied it on page load

- **Challenge:** Creating a responsive product grid
  **Solution:** Utilized CSS Grid with responsive breakpoints for optimal viewing on all devices

- **Challenge:** Form validation without page refresh
  **Solution:** Implemented JavaScript validation with user-friendly error messaging

## User Journey

A potential customer would typically:
1. Land on the homepage and learn about the brand through the hero section
2. Browse featured products or navigate to the products page
3. Use category filters to find specific clothing items
4. Read about the company story and values on the About page
5. Contact for inquiries or purchases using the contact form

## File Structure

multipage-website/
├── index.html # Homepage
├── about.html # About page
├── products.html # Products page
├── contact.html # Contact page
├── css/
│ └── style.css # Main stylesheet
├── js/
│ └── script.js # JavaScript functionality
├── images/ # Image assets
└── README.md # Project documentation


## Future Enhancements

- Shopping cart functionality with checkout process
- User authentication and accounts
- Advanced product search feature
- Payment integration
- Product reviews and ratings
- Blog section for fashion tips
- Size guide and fitting recommendations
- Wishlist functionality
- Social media integration
- Email marketing automation

## Browser Support

This website supports all modern browsers including:
- Chrome (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Edge (last 2 versions)

## Setup Instructions

1. Clone the repository: `git clone https://github.com/Keli281/multipage-website.git`
2. Open index.html in a web browser
3. Alternatively, deploy to GitHub Pages for live hosting

## License

This project is created for Natalie's Twilight Clothing Store. All rights reserved.

---

*This website was created as part of a web development assignment demonstrating skills in HTML5, CSS3, JavaScript, and responsive design principles.*
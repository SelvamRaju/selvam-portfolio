# Selvam Raju - Professional Portfolio

A stunning, modern, and responsive portfolio website showcasing my professional experience, achievements, and skills as a Tech Lead and Software Architect.

## Features

- **Modern Design**: Clean, professional UI with gradient effects and smooth animations
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Interactive Elements**: Smooth scrolling, typing animations, and scroll-triggered animations
- **Performance Optimized**: Fast loading with lazy loading and optimized animations
- **Accessibility**: Semantic HTML and ARIA-friendly components

## Sections

1. **Hero Section**: Eye-catching introduction with animated text and floating cards
2. **About Me**: Professional summary with statistics and education
3. **Experience**: Timeline-based work history with detailed responsibilities
4. **Achievements**: Showcase of 10+ awards and certifications
5. **Skills**: Comprehensive skill breakdown with animated progress bars
6. **Contact**: Contact form and social media links

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icons
- **Google Fonts**: Poppins and Space Grotesk fonts

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: A local web server for development

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/selvam-portfolio.git
cd selvam-portfolio
```

2. Open the project:
   - **Option 1**: Simply open `index.html` in your browser
   - **Option 2**: Use a local server (recommended for development)

### Using a Local Server

#### Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js (with http-server):
```bash
npx http-server -p 8000
```

#### Using VS Code:
Install the "Live Server" extension and click "Go Live" in the bottom right corner.

Then open your browser and navigate to `http://localhost:8000`

## Customization

### Update Personal Information

1. **Contact Details** (`index.html`):
   - Update email addresses in the contact section
   - Update social media links (LinkedIn, GitHub, etc.)

2. **Profile Photo**:
   - Add your profile photo and update the image paths in the HTML

3. **Content**:
   - Modify the experience, achievements, and skills sections to match your profile
   - Update the typing animation phrases in `script.js`

### Color Scheme

The color scheme can be customized by modifying CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... other variables */
}
```

## File Structure

```
selvam-portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # Interactive JavaScript
└── README.md          # This file
```

## Key Features Explained

### Typing Animation
The hero section features a dynamic typing animation that cycles through different professional titles.

### Scroll Animations
Elements fade in and animate as you scroll down the page using Intersection Observer API.

### Skill Progress Bars
Animated progress bars that fill when scrolled into view, showing proficiency levels.

### Floating Cards
Interactive floating cards in the hero section with smooth hover effects.

### Responsive Navigation
Mobile-friendly hamburger menu that adapts to different screen sizes.

### Particle Background
Subtle animated particles in the background for visual appeal.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized animations using CSS transforms
- Efficient scroll handling with requestAnimationFrame
- Lazy loading for images
- Minimal dependencies

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select the main branch as the source
4. Your site will be available at `https://yourusername.github.io/selvam-portfolio`

### Netlify

1. Drag and drop your project folder to [Netlify](https://app.netlify.com/)
2. Your site will be live instantly with a custom URL

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## Contact Form Setup

The contact form currently logs data to the console. To make it functional:

1. **Using a backend service**:
   - [Formspree](https://formspree.io/)
   - [EmailJS](https://www.emailjs.com/)
   - [Netlify Forms](https://www.netlify.com/products/forms/)

2. **Using your own backend**:
   - Uncomment the fetch code in `script.js`
   - Update the API endpoint
   - Set up your backend to handle form submissions

## Customization Tips

1. **Add Projects Section**: Create a new section to showcase your portfolio projects
2. **Blog Integration**: Add a blog section if you write technical articles
3. **Testimonials**: Include testimonials from colleagues or clients
4. **Dark/Light Mode Toggle**: Add theme switching functionality
5. **Analytics**: Add Google Analytics or similar to track visitors

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- **Design & Development**: Selvam Raju
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts](https://fonts.google.com/)

## Connect With Me

- **LinkedIn**: [linkedin.com/in/selvam-raju](https://www.linkedin.com/in/selvam-raju/)
- **GitHub**: [github.com/selvamraju](https://github.com/selvamraju)
- **Email**: officialselvam@gmail.com

## Acknowledgments

Thank you for visiting my portfolio! Feel free to fork this project and customize it for your own use.

---

Made with passion and code by Selvam Raju

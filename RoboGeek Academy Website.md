# RoboGeek Academy Website

A modern, responsive website for RoboGeek Academy - a kids robotics and coding academy. The website features a vibrant design inspired by the academy's logo colors and provides comprehensive information about programs, testimonials, and registration.

## 🎨 Design Features

- **Logo-Inspired Color Palette**: Teal (#1B7A7A) and Golden (#C8860D) colors extracted from the RoboGeek logo
- **Kid-Friendly Design**: Rounded corners, vibrant colors, and playful elements
- **Modern Typography**: Clean Poppins font family for excellent readability
- **Responsive Design**: Mobile-first approach ensuring perfect display on all devices
- **Interactive Elements**: Smooth animations, hover effects, and micro-interactions

## 📱 Responsive Features

- Mobile-responsive navigation with hamburger menu
- Flexible grid layouts that adapt to different screen sizes
- Touch-friendly buttons and form elements
- Optimized typography scaling for mobile devices

## 🏗️ Website Sections

### 1. Header & Navigation
- Logo integration with academy branding
- Smooth scrolling navigation menu
- Mobile-responsive hamburger menu

### 2. Hero Section
- Compelling headline and call-to-action
- Animated robot icon
- Gradient background using brand colors

### 3. About Us
- Academy mission and vision
- Key differentiators with emoji icons
- Professional yet approachable tone

### 4. Programs (4 Age Groups)
- **Little Builders (Ages 5-7)**: Play-based learning introduction
- **Young Engineers (Ages 8-10)**: Hands-on building and basic programming
- **Code Creators (Ages 11-13)**: Advanced robotics and text-based programming
- **Tech Innovators (Ages 14-17)**: Professional-level projects and real-world applications

### 5. Gallery
- Placeholder images for course highlights
- Grid layout with hover effects
- Ready for real photos and videos

### 6. Testimonials
- Three sample parent testimonials
- Professional card layout with author information
- Builds trust and credibility

### 7. Registration Form
- Comprehensive form collecting:
  - Child's name and age
  - Parent email and phone
  - Preferred program selection
- Form validation and user feedback
- Responsive design

### 8. Contact Information
- Phone and WhatsApp numbers
- Physical address
- Email contact
- Social media links (Facebook, Instagram, Twitter, YouTube)

### 9. Footer
- Logo and copyright information
- Consistent branding

## 🛠️ Technical Implementation

### Files Structure
```
robogeek-website/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS styling
├── script.js           # JavaScript functionality
├── images/
│   └── logo.jpg        # RoboGeek Academy logo
├── README.md           # This documentation
└── todo.md            # Development progress tracker
```

### Technologies Used
- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Interactive functionality and form handling
- **Google Fonts**: Poppins font family for typography

### Key Features
- CSS Custom Properties (CSS Variables) for consistent theming
- Mobile-first responsive design
- Smooth scrolling navigation
- Form validation
- Intersection Observer API for scroll animations
- Touch-friendly mobile interactions

## 🚀 Deployment Instructions

### Option 1: GitHub Pages Deployment

1. **Create a GitHub Repository**
   ```bash
   # Create a new repository on GitHub named "RoboGeek"
   # Clone the repository locally
   git clone https://github.com/yourusername/RoboGeek.git
   cd RoboGeek
   ```

2. **Add Website Files**
   ```bash
   # Copy all website files to the repository
   cp -r /path/to/robogeek-website/* .
   
   # Add and commit files
   git add .
   git commit -m "Initial website deployment"
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Website**
   - Your website will be available at: `https://yourusername.github.io/RoboGeek`
   - It may take a few minutes for the deployment to complete

### Option 2: Local Development Server

For local testing and development:

```bash
# Navigate to the website directory
cd robogeek-website

# Start a simple HTTP server (Python 3)
python3 -m http.server 8000

# Or using Node.js (if you have it installed)
npx serve .

# Open your browser and visit:
# http://localhost:8000
```

### Option 3: Web Hosting Services

The website can be deployed to any web hosting service that supports static websites:

- **Netlify**: Drag and drop the folder to netlify.com/drop
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI
- **Traditional Web Hosting**: Upload files via FTP

## 🎯 Customization Guide

### Updating Colors
All colors are defined as CSS custom properties in `styles.css`:
```css
:root {
    --primary-teal: #1B7A7A;
    --primary-gold: #C8860D;
    /* Modify these values to change the color scheme */
}
```

### Adding Real Images
1. Replace placeholder images in the Gallery section
2. Update the `images/` folder with actual photos
3. Modify the HTML to reference new image files

### Updating Content
- Edit text content directly in `index.html`
- Update contact information in the Contact section
- Modify program descriptions as needed

### Form Integration
To make the registration form functional:
1. Add a backend service (PHP, Node.js, etc.)
2. Update the form action attribute
3. Implement email notifications
4. Add database storage for registrations

## 📞 Support

For technical support or customization requests, please contact:
- Email: hello@robogeekacademy.com
- Phone: +1 (555) 123-ROBO

## 📄 License

© 2024 RoboGeek Academy. All rights reserved. Building the future, one robot at a time!

---

**Note**: This website is designed to be easily customizable and maintainable. All code is well-commented and follows modern web development best practices.


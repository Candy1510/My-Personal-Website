# Candy Owens' Personal Website

A vibrant, colorful personal portfolio website showcasing my journey as a Full-Stack Development student at [Atlas School](https://atlas.academy/) in Tulsa, Oklahoma. Built with vanilla HTML5 and CSS3, this site highlights my interests, creative pursuits, passion for social impact technology, and development projects.

##  Features

- **Vibrant Design** - Aqua and purple color theme with Lobster font for personality
- **Lightweight & Fast** - No frameworks or dependencies, pure HTML/CSS
- **Responsive Navigation** - Easy-to-navigate 5-page site structure
- **Personal Branding** - Unique design reflecting my creative personality
- **Media Gallery** - Photos, videos, quotes, and artwork
- **Social Links** - Connect on Facebook, LinkedIn, and GitHub
- **Favicon Assets** - Professional favicon and PWA manifest included

##  Website Sections

###  **Home** (`index.html`)
- Welcome message and brief introduction
- Profile photo and quick overview
- Links to explore other sections

###  **About Me** (`about.html`)
Discover more about who I am:
- **Interests & Hobbies** - Arts & crafts, painting, jewelry making, sewing, cooking, singing, dancing, writing, travel
- **My Passion** - Using technology to empower individuals and families affected by mental illness, addiction, and homelessness
- **My Inspiration** - My mother's remarkable journey as a programmer and her transformative impact on my life
- **Family Photos** - Personal images with my grandchildren and family

###  **Media Gallery** (`media.html`)
Showcase of creative work and inspiration:
- Family photos and personal moments
- Artwork and creative projects
- Inspirational quotes
- Videos and multimedia content

###  **Projects** (`project.html`)
Full-Stack development projects including:
- Arduino projects
- Web development work
- Educational projects from Atlas School

###  **Contact** (`contact.html`)
Get in touch with me through the contact form

##  Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling with flexbox, aqua (#00d4ff) and purple (#800080) color scheme
- **JavaScript** (minimal) - Interactive elements
- **Responsive Design** - Mobile-friendly layout
- **Favicon & PWA** - Professional web assets

##  Design Features

**Color Scheme:**
- Primary: Aqua (#00d4ff)
- Secondary: Purple (#800080)
- Accent: Teal (#0ecfc6)
- Text: Purple on light backgrounds

**Typography:**
- Font Family: 'Lobster' with sans-serif fallback

**Styling:**
- Flexible layout with CSS flexbox
- Image borders: 20px solid purple
- Rounded corners (15px border-radius)
- Responsive spacing and margins

##  Getting Started

### Prerequisites
- A code editor (VS Code, Sublime Text, etc.)
- A modern web browser
- Git (optional, for version control)

### Installation & Running Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Candy1510/My-Personal-Website.git
   cd My-Personal-Website
   ```

2. **Open in your browser**
   
   **Option A: Direct File**
   - Simply open `index.html` in your web browser
   
   **Option B: Local Server (Recommended)**
   
   Using Python:
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000 in your browser
   ```
   
   Using Node.js:
   ```bash
   npx http-server
   # Visit the provided localhost URL
   ```

3. **Start exploring!**
   - Navigate through the site using the navigation menu
   - Check out all the pages and sections

##  File Structure

```
My-Personal-Website/
├── index.html              # Home page
├── about.html              # About Me - Interests, hobbies, passion, inspiration
├── media.html              # Media Gallery - Photos, videos, quotes
├── project.html            # Projects - Development work
├── contact.html            # Contact form
├── style.css               # Main stylesheet (Aqua & Purple theme)
├── README.md               # This file
└── assets/                 # Images, favicons, and media
    ├── me.jpg              # Profile photo
    ├── family.jpg          # Family photos
    ├── mom.jpg             # Mother's photo
    ├── owen.jpg            # Grandson photos
    ├── athena.jpg          # Granddaughter photos
    ├── dawson.jpg          # Grandson photos
    ├── arduino_blue.jpg    # Arduino project images
    ├── arduino_purple.jpg
    ├── arduino_red.jpg
    ├── tent.jpg            # Outdoor/camping photo
    ├── simon.jpg           # Personal photo
    ├── plato.jpg           # Other photos
    ├── graduationvideo.mp4 # Video content
    ├── favicon.ico         # Website favicon
    ├── favicon-16x16.png
    ├── favicon-32x32.png
    ├── apple-touch-icon.png
    ├── android-chrome-*.png
    └── site.webmanifest    # PWA manifest
```

##  Customization Guide

### Edit Content

1. **Update Main Content**
   - Edit HTML files with your text editor
   - Modify text in `<p>`, `<h1>`, `<h2>` tags

2. **Change Colors**
   ```css
   /* In style.css, modify these colors */
   body {
       background-color: #e6f9ff;  /* Light aqua background */
       color: purple;              /* Text color */
   }
   
   header {
       background-color: #00d4ff;  /* Bright aqua header */
   }
   
   img {
       border: 20px solid purple;  /* Purple image borders */
   }
   ```

3. **Update Fonts**
   - The site uses 'Lobster' font from Google Fonts
   - Change `font-family` in `style.css` to use different fonts

4. **Replace Images**
   - Add new images to the `assets/` folder
   - Update `src` attributes in HTML files to point to new images

### Adding New Pages

1. Create a new HTML file (e.g., `blog.html`)
2. Copy the structure from an existing page
3. Add navigation links in all HTML files

### Updating Navigation

To add or remove navigation items, update the navbar in all HTML files:

```html
<nav class="navbar">
    <ul>
        <li><button><a href="index.html">Home</a></button></li>
        <li><button><a href="about.html">About</a></button></li>
        <li><button><a href="media.html">Media Gallery</a></button></li>
        <li><button><a href="contact.html">Contact</a></button></li>
        <li><button><a href="project.html">Projects</a></button></li>
    </ul>
</nav>
```

##  Deployment

### GitHub Pages (Recommended - FREE)

1. Push repository to GitHub (already done!)
2. Go to repository **Settings** → **Pages**
3. Select `main` branch as the source
4. Your site will be live at: `https://Candy1510.github.io/My-Personal-Website/`

### Other Hosting Options

- **Netlify** - Free hosting with automatic deployments
- **Vercel** - Free static hosting with GitHub integration
- **Traditional Hosting** - Upload via FTP to your hosting provider

##  Responsive Design

The website is designed to work on multiple screen sizes:

**Desktop**
- Full navigation and image displays
- Maximum width container (1200px max)

**Tablet & Mobile**
- Stacked layout for smaller screens
- Responsive navigation
- Properly sized images for touch devices

**Testing:**
- Open Developer Tools (F12) in your browser
- Click the mobile device icon to test different screen sizes

##  Accessibility Features

- Semantic HTML tags (`<header>`, `<nav>`, `<main>`, `<footer>`)
- Alt text on all images
- Proper heading hierarchy
- Good color contrast (purple text on light backgrounds)
- Descriptive link text

##  SEO Optimization

The website includes:
- Meta charset and viewport tags
- Favicon for better branding
- Semantic HTML structure
- Descriptive page titles
- Alt text on all images

**To improve further:**
- Add meta descriptions to each page
- Include Open Graph tags for social sharing
- Create a `sitemap.xml` for search engines

##  Contact Form Setup

The contact form on `contact.html` can be connected to:

- **Formspree** - Add your email: `formspree.io/your-email@example.com`
- **EmailJS** - Client-side email sending
- **Netlify Forms** - Built-in form handling
- **Backend Service** - Create your own form handler

##  What I'm Learning

As a Full-Stack Development student at Atlas School, I'm working with:
- Frontend: HTML, CSS, JavaScript, React
- Backend: Python, Node.js, databases
- Full-stack projects combining multiple technologies
- Git and version control
- Responsive web design principles

##  My Goals & Passion

My ultimate goal is to **leverage technology to empower others**, particularly individuals and families affected by:
- Mental health challenges
- Addiction
- Homelessness

I aim to create apps and websites that:
- Provide accessible tools and guidance
- Help people navigate available services
- Support recovery and self-sufficiency
- Make a positive impact on communities

This website is just the beginning of that journey!

##  Resources & Learning

- [MDN Web Docs](https://developer.mozilla.org/) - HTML & CSS reference
- [CSS Tricks](https://css-tricks.com/) - Tips and tutorials
- [Can I Use](https://caniuse.com/) - Browser compatibility
- [Coolors.co](https://coolors.co/) - Color palette generator
- [Font Pair](https://www.fontpair.co/) - Font combinations
- [Atlas School](https://atlas.academy/) - My development school

##  License

This project is open source. Feel free to use it as inspiration for your own personal website!

© 2025 Candy Owens

##  Connect With Me

Let's stay connected! Find me on:

- **LinkedIn**: [Candy Owens](https://www.linkedin.com/in/candy-owens-35a2a2220/)
- **GitHub**: [@Candy1510](https://github.com/Candy1510/)
- **Facebook**: [Candy Owens](https://www.facebook.com/profile.php?id=61564370977860)

##  Troubleshooting

**Issue: Styles not loading?**
- Clear your browser cache (Ctrl+Shift+Del)
- Try opening in an incognito/private window

**Issue: Images not showing?**
- Check that image paths are correct (relative to HTML file)
- Ensure images exist in the `assets/` folder
- Use browser DevTools to check for 404 errors

**Issue: Navigation links not working?**
- Verify HTML file names match the links
- Check that files are in the correct directory

**Issue: Responsive layout looks wrong?**
- Test with browser DevTools (F12)
- Check device emulation to see mobile view
- Verify viewport meta tag is in the HTML head

##  Thank You

Thank you for visiting my personal website! I hope you've enjoyed learning about me, my journey, and my passion for using technology to make a positive impact.

Feel free to reach out through the contact form, and don't forget to connect with me on social media!

---

**Last Updated:** January 2025

**Happy Coding! 🚀**

# Meechai Anukkamontree - Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and dynamic navigation
- **Performance Optimized**: Fast loading times and efficient animations
- **Accessible**: Semantic HTML and keyboard navigation support

## Sections

1. **Home/Hero**: Eye-catching introduction with gradient background
2. **About**: Personal information and background
3. **Experience**: Timeline of professional and educational journey
4. **Projects**: Showcase of your work and achievements
5. **Contact**: Easy ways to get in touch

## Customization

### Update Your Information

1. **Personal Details** (`index.html`):
   - Replace "your.email@example.com" with your actual email
   - Update LinkedIn URL: "https://linkedin.com/in/yourprofile"
   - Update GitHub URL: "https://github.com/yourprofile"
   - Modify the "Location" and "Interests" in the About section

2. **About Section**:
   - Edit the paragraphs in the About section to tell your story
   - Replace the SVG placeholder with your actual photo

3. **Experience/Timeline**:
   - Update the timeline items with your actual education and work experience
   - Add or remove timeline items as needed

4. **Projects**:
   - Replace placeholder projects with your actual work
   - Update project titles, descriptions, and tags
   - Add links to project repositories or live demos

5. **Colors** (`styles.css`):
   ```css
   :root {
       --primary-color: #667eea;    /* Change to your preferred color */
       --secondary-color: #764ba2;  /* Change to your preferred color */
   }
   ```

### Adding Your Photo

Replace the SVG placeholder in the About section with an actual image:

```html
<div class="about-image">
    <img src="path/to/your/photo.jpg" alt="Meechai Anukkamontree">
</div>
```

## Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Meechai.git
   cd Meechai
   ```

2. **Open in browser**:
   Simply open `index.html` in your web browser, or use a local server:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. **View your site**:
   Navigate to `http://localhost:8000` in your browser

## Deployment

### GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** > **Pages**
3. Under "Source", select the branch (usually `main`)
4. Click **Save**
5. Your site will be available at `https://yourusername.github.io/Meechai/`

### Netlify

1. Sign up for a free account at [Netlify](https://www.netlify.com)
2. Click **New site from Git**
3. Connect your GitHub repository
4. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: `/`
5. Click **Deploy site**

### Vercel

1. Sign up at [Vercel](https://vercel.com)
2. Click **Import Project**
3. Import your GitHub repository
4. Click **Deploy**

## File Structure

```
Meechai/
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # Interactive functionality
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Google Fonts (Inter)

## Performance

- Optimized animations using CSS transforms
- Throttled scroll events for better performance
- Lazy loading for scroll-triggered animations
- Minimal dependencies (no frameworks required)

## License

This project is open source and available for personal use.

## Contact

Feel free to reach out if you have any questions or suggestions!

---

Built with passion and code by Meechai Anukkamontree

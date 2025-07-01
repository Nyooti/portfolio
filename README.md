# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Sections Included**:
  - Hero section with introduction
  - About section with personal information
  - Skills section showcasing technical abilities
  - Projects section with portfolio items and images
  - Work experience timeline
  - Education and certifications
  - Contact form with social links
  - **Download Resume**: Prominent button in the navbar for downloading the latest resume (PDF)

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start customizing the content

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "THOMAS OWINO" throughout the file
- **Title/Role**: Update the hero subtitle
- **Description**: Modify the about section text
- **Contact Information**: Update email, phone, and location
- **Social Links**: Add your actual social media URLs

### 2. Project Images

- All images are stored in the `images/` folder for better organization.
- Update project image paths in `index.html` to use the `images/` folder, e.g.:
  ```html
  <img src="images/e commerce.jpg" alt="E-commerce Website">
  ```
- Add or replace images as needed for each project.

### 3. Resume Download

- The resume download button is located in the navbar.
- To update your resume, replace `Thomas Owino Resume.pdf` in the project root with your latest PDF.
- The button will always offer the latest version for download.

### 4. Skills, Experience, and Education

- Update the skills, work experience, and education sections in `index.html` to reflect your background.

### 5. Styling

Customize the appearance in `styles.css`:

- **Colors**: Update the color scheme by changing CSS variables
- **Fonts**: Modify font families and sizes
- **Layout**: Adjust spacing and grid layouts
- **Animations**: Customize transition effects

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
├── images/             # All project and background images
│   ├── background image 2.jpg
│   ├── background image 3.jpg
│   ├── background image image 1.jpg
│   ├── e commerce.jpg
│   ├── image 1.JPG
│   ├── image 2.JPG
│   ├── image 3.JPG
│   ├── image 4.jpg
│   ├── image 5.jpg
│   ├── smart attendance system.jpg
│   ├── task management.jpg
│   └── weather dashboard.jpg
├── Thomas Owino Resume.pdf   # Downloadable resume
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Deployment

### Local Development

Simply open `index.html` in your browser to view locally.

### GitHub Pages

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main` or `master`)
5. Your portfolio will be available at `https://username.github.io/repository-name`

### Other Hosting Options

- Netlify
- Vercel
- AWS S3
- Any web hosting service

## Customization Tips

1. **Keep it Professional**: Use high-quality images and professional language
2. **Be Concise**: Keep descriptions clear and to the point
3. **Show Results**: Include metrics and achievements where possible
4. **Regular Updates**: Keep your portfolio current with new projects and skills
5. **Mobile First**: Test on mobile devices to ensure good experience

## Contact Form

The contact form is currently set up for demonstration. To make it functional:

1. Set up a backend service (Node.js, PHP, etc.)
2. Configure email sending functionality
3. Update the form action and method in HTML
4. Add form validation and error handling

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community!

## Support

If you need help customizing your portfolio, check out:

- HTML/CSS documentation
- JavaScript tutorials
- Web development communities
- Portfolio design inspiration websites

---
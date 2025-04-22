# Portfolio Website for BSC(Hons) Computing Student

A modern, responsive portfolio website designed for a BSC(Hons) Computing student at Ithari International College, Nepal.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Smooth scrolling navigation
- Animated sections on scroll
- Contact form
- Skills showcase
- Project portfolio
- Social media integration

## Customization

### Personal Information
1. Open `index.html` and update the following:
   - Your name in the footer
   - Your email address
   - Your phone number
   - Your social media links
   - Your profile picture (replace `profile-placeholder.jpg`)

### Projects
1. In the Projects section of `index.html`, update the project cards with:
   - Project titles
   - Project descriptions
   - GitHub repository links
   - Live demo links

### Skills
1. In the Skills section of `index.html`, update the skills lists with your actual skills
2. You can add or remove skill categories as needed

### Styling
1. To change the color scheme, update the CSS variables in `styles.css`:
   ```css
   :root {
       --primary-color: #2563eb;
       --secondary-color: #1e40af;
       --text-color: #1f2937;
       --light-text: #6b7280;
       --background: #ffffff;
       --section-bg: #f3f4f6;
   }
   ```

## Setup

1. Clone this repository or download the files
2. Replace the placeholder content with your information
3. Add your profile picture as `profile-placeholder.jpg` in the root directory
4. Open `index.html` in a web browser to view your portfolio

## Contact Form

The contact form currently shows a success message but doesn't actually send emails. To make it functional:

1. Set up a backend server to handle form submissions
2. Update the form handling in `script.js` to send data to your server
3. Add proper error handling and validation

## Browser Support

This portfolio website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. 
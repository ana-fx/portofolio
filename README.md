# Portfolio - Aan Rachmatullah Pratama

A modern, responsive portfolio website with a tech-themed design, showcasing my skills, experience, and projects as a Full Stack Developer.

![Portfolio Preview](preview.png)

## Features

- **Tech-inspired design** - Dark theme with code-like styling and tech/programming-inspired UI elements
- **Responsive layout** - Works perfectly on all devices and screen sizes
- **Interactive elements** - Flip card for personal photo, interactive journey visualization, tech dashboard
- **Animated sections** - Smooth animations and transitions between all portfolio sections
- **Digital rain effect** - Matrix-style animations in the background of specific sections
- **Terminal-style components** - Terminal windows for skills display and code animations

## Sections

- **Header** - Navigation with tech-inspired styling
- **Hero** - Two-column layout with interactive flip card and introduction
- **About Me** - Personal information in a tech dashboard layout
- **Experience** - Creative journey path visualization of career progression
- **Skills** - Tech dashboard with radar chart, terminal window, and tech level indicators
- **Contact/Footer** - Creative tech-themed design with animated elements

## Technologies Used

- HTML5
- Tailwind CSS
- JavaScript
- Font Awesome icons
- Google Fonts

## Installation and Usage

1. Clone the repository:
   ```
   git clone https://github.com/ana-fx/portofolio.git
   ```

2. Open `index.html` in your web browser to view the portfolio.

3. Customize the content in `index.html` to match your personal information, skills, and experience.

## Customization

### Changing Color Scheme

The primary color scheme can be modified in the Tailwind config section at the top of the HTML file:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#111111',
                secondary: '#f5f5f5',
                accent: '#333333',
                dark: '#000000',
                light: '#ffffff',
            },
            // ... other config
        }
    }
}
```

### Adding Your Photo

Replace the photo in the flip card section with your own image by updating the image source:

```html
<img src="YOUR_IMAGE_PATH" alt="Your Name" class="w-full h-full object-cover">
```

## License

MIT License

## Connect with Me

- Email: aanjr38@gmail.com
- GitHub: [ana-fx](https://github.com/ana-fx)

---

© 2023 Aan Rachmatullah Pratama. All rights reserved. 
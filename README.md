# Road Ready Driving School Website

A modern, responsive website for a driving school featuring an embedded Calendly booking system.

## Features

- **Responsive Design**: Works on all devices (mobile, tablet, desktop)
- **Modern UI**: Clean, professional interface with smooth animations
- **Online Booking**: Integrated Calendly for easy lesson scheduling
- **Contact Form**: For inquiries and questions
- **Course Information**: Details about available driving courses
- **Testimonials**: Showcase student experiences

## Technologies Used

- HTML5
- CSS3 (with CSS variables, Flexbox, and Grid)
- JavaScript (ES6+)
- Calendly API for booking integration
- Font Awesome for icons

## Setup

1. Clone the repository
2. Open `index.html` in a web browser

## Customization

### Calendly Integration

The website currently uses a placeholder Calendly URL. To connect your own Calendly account:

1. Sign up for Calendly (https://calendly.com)
2. Set up your availability and event types
3. Replace the Calendly URL in the `index.html` file:
   ```html
   <div class="calendly-inline-widget" data-url="YOUR_CALENDLY_URL_HERE" style="min-width:320px;height:700px;"></div>
   ```

### Images

Replace the placeholder images in the `images` folder with your own:
- `hero-bg.jpg`: Hero background image
- `instructor.jpg`: Instructor or school image for About section
- `testimonial1.jpg`, `testimonial2.jpg`, `testimonial3.jpg`: Student testimonial images

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License.
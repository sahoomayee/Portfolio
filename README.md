# Portfolio Website - Tanmayee Sahoo

A modern, responsive portfolio website showcasing my skills and experience as a DevOps & Cloud Engineer.

## Features

- 🌗 Dark/Light theme toggle
- 📱 Fully responsive design
- ✨ Smooth animations and transitions
- 📊 Interactive skill bars
- 📬 Working contact form using EmailJS
- 🎯 Smooth scroll navigation

## Setup Instructions

### 1. Basic Setup
1. Clone the repository or download the files
2. Open the project folder in your preferred code editor
3. No build process required - pure HTML, CSS, and JavaScript

### 2. EmailJS Setup (for Contact Form)

The contact form uses EmailJS to send emails. Follow these steps to configure it:

1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Set up an Email Service:
   - Go to "Email Services" tab
   - Add a new service (Gmail, Outlook, etc.)
   - Note down the Service ID: `service_djiki1v`

3. Create an Email Template:
   - Go to "Email Templates" tab
   - Create a new template
   - Use these variables in your template:
     - `{{from_name}}` - Sender's name
     - `{{from_email}}` - Sender's email
     - `{{message}}` - Message content
   - Note down the Template ID: `template_hrii0e9`

4. Get your Public Key:
   - Go to "Account" → "API Keys"
   - Note down your Public Key: `uv6m6sBQpPDGCUcBK`

These values are already configured in `script.js`. If you fork this project, replace them with your own credentials.

### 3. Testing the Contact Form

1. Open `index.html` in a modern browser
2. Fill out the contact form:
   - Name
   - Email
   - Message
3. Click "Send Message"
4. Check browser console (F12) for any errors
5. Verify email delivery to your configured address

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── style.css          # Styles and animations
├── script.js          # JavaScript functionality
├── README.md         # This documentation
└── assets/           # Images and resources
```

## Customization

### Modifying Content
1. Edit `index.html` to update:
   - Personal information
   - Skills and percentages
   - Portfolio projects
   - Contact details

### Changing Theme Colors
1. Open `style.css`
2. Modify the root variables:
   ```css
   :root {
     --bg: #f4eded;
     --card: #0b0b0b;
     --muted: #9aa4a0;
     --accent: #00ff83;
     --accent-2: #00d36b;
   }
   ```

### Adding New Sections
1. Follow the existing HTML structure in `index.html`
2. Add corresponding styles in `style.css`
3. Add any needed JavaScript functionality in `script.js`

## Troubleshooting

### Contact Form Issues
1. Check browser console (F12) for errors
2. Verify EmailJS credentials in `script.js`
3. Ensure template variables match exactly
4. Check EmailJS dashboard for service status

### Display Issues
1. Clear browser cache
2. Check browser console for errors
3. Verify all CSS and JS files are loading
4. Test in different browsers

## Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid)
- JavaScript (ES6+)
- EmailJS for contact form
- Google Fonts (Inter)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal portfolio. Attribution appreciated but not required.
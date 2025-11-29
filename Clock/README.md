# Beautiful Clock

A stunning, interactive clock application featuring both analog and digital displays with smooth animations and multiple themes.

## Features

- **Analog Clock**: Beautiful circular clock with smooth hand movements
- **Digital Clock**: Clear time display with date and day information
- **Multiple Themes**: Light, Dark, and Ocean themes to suit your preference
- **Time Formats**: Switch between 12-hour and 24-hour formats
- **Toggle Seconds**: Show or hide seconds display
- **Keyboard Shortcuts**: Quick access to common features
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Fluid transitions and micro-interactions

## Keyboard Shortcuts

- `1` - Switch to 12-hour format
- `2` - Switch to 24-hour format
- `S` - Toggle seconds display
- `T` - Cycle through themes

## Deployment

This project is optimized for Netlify deployment. Here's how to deploy it:

### Method 1: Drag and Drop (Easiest)

1. Build your project locally (if needed)
2. Go to [Netlify](https://netlify.com)
3. Drag and drop the entire project folder onto the deployment area
4. Your site will be live instantly!

### Method 2: Git Integration

1. Push your code to GitHub, GitLab, or Bitbucket
2. Connect your repository to Netlify
3. Netlify will automatically deploy your site on every push

### Method 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy your site
netlify deploy --prod --dir=.
```

## Project Structure

```
Clock/
├── index.html          # Main application file
├── netlify.toml        # Netlify configuration
├── clock.html          # Original file (redirects to index.html)
└── README.md           # This file
```

## Configuration

The `netlify.toml` file includes:

- Security headers for enhanced protection
- Caching strategies for optimal performance
- Redirect from `clock.html` to `index.html`

## Browser Support

This clock works on all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: No dependencies, pure JavaScript
- **Responsive Design**: Mobile-first approach

## Performance

- Lightweight single-file application
- Optimized animations using CSS transforms
- Efficient JavaScript with minimal DOM manipulation
- Fast loading times with inline CSS and JavaScript

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Enjoy your beautiful clock!** 🕐

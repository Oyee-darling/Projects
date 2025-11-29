# Scientific Calculator

A powerful, feature-rich scientific calculator with advanced mathematical functions, memory operations, and calculation history. Perfect for students, engineers, and professionals.

## Features

### Basic Operations
- Arithmetic operations: Addition, Subtraction, Multiplication, Division
- Parentheses for complex expressions
- Decimal point support
- Clear and backspace functionality

### Scientific Functions
- **Trigonometric**: sin, cos, tan and their inverses (asin, acos, atan)
- **Hyperbolic**: sinh, cosh, tanh
- **Logarithmic**: log (base 10), ln (natural log)
- **Exponential**: exp (e^x), square root
- **Other**: Factorial, absolute value, reciprocal, percentage
- **Constants**: π (pi), e (Euler's number)

### Advanced Features
- **Memory Operations**: MC (Memory Clear), MR (Memory Recall), M+, M-, MS (Memory Store)
- **Angle Modes**: Degrees, Radians, Gradians
- **Calculation History**: Track last 10 calculations
- **Keyboard Support**: Full keyboard input for efficient calculations
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Keyboard Shortcuts

- **Numbers**: 0-9
- **Operations**: +, -, *, /
- **Special Keys**:
  - `Enter` or `=`: Calculate result
  - `Escape` or `C`: Clear display
  - `Backspace`: Delete last digit
  - `(`, `)`: Parentheses
  - `P`: Insert π (pi)
  - `E`: Insert e (Euler's number)

## Deployment

This calculator is optimized for Netlify deployment. Here's how to deploy it:

### Method 1: Drag and Drop (Easiest)

1. Go to [Netlify](https://netlify.com)
2. Drag and drop the entire `Calculator` folder onto the deployment area
3. Your calculator will be live instantly!

### Method 2: Git Integration

1. Push your code to GitHub, GitLab, or Bitbucket
2. Connect your repository to Netlify
3. Netlify will automatically deploy your calculator on every push

### Method 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy your calculator
netlify deploy --prod --dir=.
```

## Project Structure

```
Calculator/
├── index.html          # Main calculator application
├── netlify.toml        # Netlify configuration
├── calculator.html     # Original file (redirects to index.html)
└── README.md           # This file
```

## Configuration

The `netlify.toml` file includes:

- Security headers for enhanced protection
- Caching strategies for optimal performance
- Redirect from `calculator.html` to `index.html`

## Browser Support

This calculator works on all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Technologies Used

- **HTML5**: Semantic markup and modern input handling
- **CSS3**: Advanced styling with gradients, animations, and responsive design
- **Vanilla JavaScript**: Pure JavaScript with no external dependencies
- **CSS Grid**: Modern layout system for button arrangement
- **Flexbox**: Flexible layout for responsive design

## Performance

- Lightweight single-file application
- Efficient JavaScript with minimal DOM manipulation
- Fast loading times with inline CSS and JavaScript
- Optimized animations using CSS transforms
- Smart caching strategies for repeat visits

## Usage Examples

### Basic Calculations
```
2 + 3 = 5
10 * 5 = 50
100 / 4 = 25
```

### Scientific Functions
```
sin(30) = 0.5 (in degrees mode)
log(100) = 2
sqrt(16) = 4
5! = 120
```

### Complex Expressions
```
(2 + 3) * 4 = 20
sin(45) * cos(45) = 0.5
log(100) + ln(e) = 3
```

## Error Handling

The calculator includes comprehensive error handling:
- Division by zero protection
- Invalid input detection
- Mathematical domain errors
- Automatic error recovery with timeout

## Mobile Optimization

- Touch-friendly button sizes
- Responsive grid layout
- Optimized for small screens
- Smooth touch interactions
- Portrait and landscape support

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Enjoy your powerful scientific calculator!** 🧮

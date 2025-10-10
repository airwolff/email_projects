# email_projects

Email templates for Wolff Creative photography studio plus portfolio showcase. Production templates handle client bookings, payments, and gallery delivery. Portfolio section demonstrates advanced email development skills (interactive, animations, dark mode). MJML-based with HTML output. Real business tools and technical showcase combined.

## 📁 Project Structure

```
email_projects/
├── transactional/          # Business transactional emails
│   ├── booking-confirmation.mjml
│   ├── payment-receipt.mjml
│   └── gallery-delivery.mjml
├── campaigns/              # Marketing campaign emails
│   └── holiday-special.mjml
├── portfolio/              # Interactive showcase emails
│   └── interactive-showcase.mjml
├── dist/                   # Compiled HTML output
│   ├── index.html         # Preview browser
│   ├── transactional/
│   ├── campaigns/
│   └── portfolio/
└── package.json           # Build scripts and dependencies
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation

```bash
# Install dependencies
npm install
```

### Development

```bash
# Build all MJML templates to HTML
npm run build

# Watch for changes and auto-rebuild
npm run build:watch

# Start browser preview server
npm run preview

# Development mode (watch + preview)
npm run dev
```

The dev command will:
1. Build all MJML templates
2. Watch for file changes and rebuild automatically
3. Start a local server at `http://localhost:3000`
4. Auto-refresh browser when files change

## 📧 Email Templates

### Transactional Emails
Production-ready templates for client communication:

- **booking-confirmation.mjml** - Sent when clients book a photography session
- **payment-receipt.mjml** - Payment confirmation with transaction details
- **gallery-delivery.mjml** - Notification when photos are ready for download

### Campaign Emails
Marketing and promotional templates:

- **holiday-special.mjml** - Seasonal campaign with special offers and packages

### Portfolio Showcase
Technical demonstration of advanced email development:

- **interactive-showcase.mjml** - Features CSS animations, hover effects, dark mode support, and responsive design

## 🛠️ Technology Stack

- **MJML 4.16** - Responsive email framework
- **mjml-cli** - Command-line interface for MJML
- **browser-sync** - Live-reload development server
- **concurrently** - Run multiple npm scripts simultaneously

## 📦 NPM Scripts

| Script | Description |
|--------|-------------|
| `npm run build` | Compile all MJML files to HTML |
| `npm run build:watch` | Watch and rebuild on changes |
| `npm run preview` | Start local preview server |
| `npm run dev` | Full development environment |

## 🎨 Features

### Transactional Templates
- Clean, professional design
- Mobile-responsive
- Email client compatible
- Brand colors and styling
- Clear call-to-action buttons

### Interactive Portfolio
- CSS animations (fade-in effects)
- Hover interactions
- Dark mode support
- Responsive image grids
- Social media integration
- Professional photography showcase

## 📝 Customization

To customize templates:

1. Edit `.mjml` files in the respective folders
2. Run `npm run build` to compile to HTML
3. Preview changes in `dist/` folder or use `npm run dev`

### Brand Colors
- Primary: `#2c2c2c` (dark gray)
- Accent: `#d4af37` (gold)
- Background: `#f4f4f4` (light gray)

## 🌐 Browser Preview

After running `npm run dev`, open `http://localhost:3000` to see:
- Visual index of all email templates
- Click any template to preview in browser
- Test responsive design and interactions

## 📤 Deployment

The compiled HTML files in `dist/` are ready to use with any email service provider (ESP):
- Mailchimp
- SendGrid
- Mailgun
- Campaign Monitor
- Or any custom email system

## 🔧 Development Tips

1. **Testing**: Always test emails in multiple email clients (Gmail, Outlook, Apple Mail, etc.)
2. **Images**: Replace placeholder images with actual photography
3. **Content**: Update bracketed placeholders like `[Client Name]` with dynamic data from your ESP
4. **Responsive**: MJML handles responsive design automatically
5. **Inline CSS**: MJML compiles to inline CSS for maximum email client compatibility

## 📄 License

ISC

## 🤝 Contributing

This is a personal project for Wolff Creative Photography Studio. The portfolio section demonstrates email development capabilities.

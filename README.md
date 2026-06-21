# UnderR∞t Energy - Master Roadmap Dashboard

> A premium strategic roadmap dashboard transforming UnderR∞t Energy Pvt. Ltd. from an offline solar & EPC company into one of India's most trusted renewable energy brands.

## 🌟 Overview

UnderR∞t Energy Master Roadmap Dashboard is a comprehensive strategic planning and tracking tool designed to visualize the company's transformation journey. It provides real-time insights into project phases, KPIs, investment tracking, risk management, and resource planning across a 12-month roadmap.

**Mission:** Infinite Energy. Sustainable Future.

## ✨ Key Features

- **📊 Interactive Dashboard** - Real-time overview of project progress and key metrics
- **🗺️ Dynamic Roadmap Timeline** - Visual representation of all project phases with status tracking
- **📈 KPI Monitoring** - Track performance indicators across all business units
- **💰 Investment Tracker** - Monitor budget allocation and spending across phases
- **⚠️ Risk Management** - Identify and track risks with mitigation strategies
- **👥 Resource Planning** - Manage team allocation and resource requirements
- **🔍 Progress Analytics** - Detailed progress visualization using Chart.js
- **🌓 Dark/Light Theme** - Professional theming with user preference toggle
- **📱 Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **♿ Accessible Design** - WCAG compliant with semantic HTML and ARIA labels

## 📁 Project Structure

```
root-energy-plan/
├── index.html                 # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css         # Main stylesheet with design system
│   ├── js/
│   │   └── scripts.js        # Application logic and interactivity
│   └── favicon/              # Branding assets
│       ├── favicon.svg
│       ├── favicon-96x96.png
│       ├── favicon.ico
│       ├── apple-touch-icon.png
│       └── site.webmanifest
└── README.md                  # This file
```

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Visualization**: Chart.js for data charts and analytics
- **Icons**: Lucide Icons for consistent iconography
- **Styling**: Modern CSS with CSS Variables and Glassmorphism
- **Design**: Responsive grid layout with mobile-first approach
- **Theme System**: Dark mode by default with light mode support

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server-side dependencies required
- Optional: Local development server (Live Server, Python HTTP Server, etc.)

### Installation

1. **Clone or download the project**
   ```bash
   git clone <repository-url>
   cd root-energy-plan
   ```

2. **Open in browser**
   - Double-click `index.html` to open directly, or
   - Use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. **Access the dashboard**
   - Open `http://localhost:8000` in your browser
   - The dashboard will load with the dark theme by default

## 📖 Usage

### Navigation

- **Dashboard** - Overview of all metrics and progress
- **Progress** - Detailed progress tracking across phases
- **Roadmap** - Visual timeline of all project phases
- **KPIs** - Key performance indicators dashboard
- **Investment** - Budget and investment tracking
- **Risk** - Risk assessment and mitigation
- **Vision** - Long-term company vision and goals

### Features

- **Theme Toggle** - Click the theme toggle button to switch between dark and light modes
- **Mobile Menu** - Hamburger menu provides navigation on smaller screens
- **Responsive Layout** - Dashboard adapts to all screen sizes
- **Section Navigation** - Use navigation links to jump to different sections

## 📊 Project Roadmap Overview

The Master Roadmap spans 12 months across multiple strategic phases:

### Phase 1: Foundation (0-3 Months)
- Brand establishment and digital infrastructure
- Status: **COMPLETED**
- Goal: Ready for public launch

### Phase 2: Digital Identity (0-3 Months)
- Search, maps, and social discovery
- Status: **ACTIVE**
- Goal: Brand searchability and discoverability

### Phase 3: Website Launch (0-3 Months)
- Fast, responsive lead-generation website
- Status: **ACTIVE**
- Goal: Central digital conversion asset

### Phase 4: Analytics Foundation (0-3 Months)
- Measurement systems setup
- Status: **PLANNED**
- Goal: Measurable digital growth

### Phase 5: SEO Foundation (0-3 Months)
- Technical SEO and search coverage
- Status: **PLANNED**
- Goal: Search engine visibility

### Phase 6: Local SEO Domination (3-6 Months)
- City-level local search visibility
- Status: **PLANNED**
- Goal: Local search dominance

### Phase 7: Content Engine (3-6 Months)
- Content marketing and engagement
- Status: **PLANNED**
- Goal: Thought leadership

*And more phases covering paid advertising, lead nurturing, conversion optimization, and brand authority.*

## 🎨 Design System

### Color Palette

- **Primary**: Orange (#f59e0b)
- **Accent**: Green (#228b22)
- **Background**: Navy (#0f172a)
- **Success**: Emerald (#10b981)
- **Warning**: Amber (#f59e0b)
- **Error**: Red (#ef4444)

### Typography

- **Font Family**: Inter, system UI fonts
- **Responsive Typography**: Scales with viewport
- **Color System**: Slate palette for text variants

### Spacing & Radius

- **Border Radius**: xl (28px), lg (22px), md (16px), sm (12px)
- **Container Max**: 1440px
- **Header Height**: 76px

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Modifying the Roadmap

Edit the `phases` array in `assets/js/scripts.js` to update project phases, timelines, and KPIs.

### Updating Styling

Modify CSS variables in `assets/css/style.css` under the `:root` selector to change colors, spacing, and other design tokens.

### Adding New Sections

1. Add a new `<section>` in `index.html`
2. Add corresponding navigation link
3. Add styling in `assets/css/style.css`
4. Add interactivity in `assets/js/scripts.js` if needed

## 🌐 Deployment

### Static Hosting Options

The dashboard can be deployed to:

- **Netlify** - Drag and drop deployment
- **Vercel** - Optimal for static sites
- **GitHub Pages** - Free hosting with git integration
- **Firebase Hosting** - Fast and reliable
- **AWS S3** - Scalable cloud storage
- **Traditional Web Hosting** - Any provider with FTP access

### Deployment Steps

1. Build/prepare files (no build step required)
2. Upload all files to your hosting provider
3. Configure domain and DNS
4. Enable HTTPS for security

## 🚦 Performance

- **Fast Load Times**: Optimized CSS and JavaScript
- **Core Web Vitals**: Optimized for Google's Web Vitals
- **Image Optimization**: Minimal image assets
- **Lazy Loading**: Chart.js loaded on-demand
- **Responsive Design**: Optimized for all devices

## ♿ Accessibility

- WCAG 2.1 Level AA compliant
- Semantic HTML structure
- ARIA labels for interactive elements
- Keyboard navigation support
- High contrast theme support
- Readable font sizes and spacing

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow the existing code style
- Maintain responsive design across all breakpoints
- Ensure accessibility compliance
- Test on multiple browsers
- Update documentation as needed

## 📝 License

This project is the proprietary property of UnderR∞t Energy Pvt. Ltd.

## 📧 Contact

**UnderR∞t Energy Pvt. Ltd.**

- **Website**: [Your website URL]
- **Email**: contact@underroot-energy.com
- **LinkedIn**: [LinkedIn Profile]
- **Phone**: [Contact Number]

## 🙏 Acknowledgments

- Chart.js for powerful charting capabilities
- Lucide Icons for beautiful icon library
- Inter font by Rasmus Andersson
- Design inspiration from modern dashboard patterns

---

<div align="center">

**Infinite Energy. Sustainable Future.** ∞

© 2024 UnderR∞t Energy Pvt. Ltd. All rights reserved.

</div>

# Keeta Delivery Guidelines Dashboard

A multilingual React dashboard for Keeta delivery riders with comprehensive guidelines and best practices.

## Features

- **Multilingual Support**: English, Arabic, Urdu, Bengali, and Hindi
- **RTL Support**: Proper right-to-left text direction for Arabic and Urdu
- **Responsive Design**: Works on all screen sizes
- **Modern UI**: Built with Tailwind CSS and Lucide React icons
- **Interactive Guidelines**: Clear, color-coded sections for easy navigation

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Modern icon library
- **PostCSS** - CSS processing

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173/`

### Build for Production

Build the application for production:
```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

Preview the production build locally:
```bash
npm run preview
```

## Project Structure

```
riders-instruction-dashboard/
├── src/
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles and Tailwind directives
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── postcss.config.js    # PostCSS configuration
```

## Guidelines Covered

The dashboard provides guidance on:

1. **Wrong Order Protocol** - Steps to take if another rider takes your order
2. **Delivery Timing** - Never mark orders as delivered before handover
3. **Prevention Guidelines** - How to prevent wrong order delivery
4. **Best Practices** - Checklist for successful deliveries
5. **Detailed Tips** - Comprehensive delivery instructions

## Language Support

- 🇬🇧 English
- 🇸🇦 Arabic (العربية)
- 🇵🇰 Urdu (اردو)
- 🇧🇩 Bengali (বাংলা)
- 🇮🇳 Hindi (हिन्दी)

## License

This project is proprietary and confidential.

# Modern Portfolio Website

A sleek and interactive portfolio website built with React, TypeScript, and Tailwind CSS, featuring smooth animations and a modern design.

## 🚀 Tech Stack

- **Frontend Framework:** React with TypeScript
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **Text Effects:** Typewriter Effect
- **Contact Form:** EmailJS
- **Build Tool:** Vite

## ✨ Features

- 🌓 Dark/Light mode toggle
- 🖱️ Custom cursor effects
- 📱 Fully responsive design
- 🎯 Smooth scroll navigation
- 🎨 Modern gradient backgrounds
- ✉️ Working contact form
- 💫 Scroll reveal animations
- 🎭 Interactive UI elements

##  🛠️️ Installation & Setup

1. Clone the repository
```bash
git clone <your-repo-url>
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and include your EmailJS credentials:
```
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key
```

4. Start the development server
```bash
npm run dev
```

## 📋 Project Structure

- `/src/components/` - React components for each section
  - `Hero.tsx` - Landing section with introduction
- `About.tsx` - Overview of skills and expertise
- `Education.tsx` - Educational background
- `Experience.tsx` - Professional experience
- `Projects.tsx` - Featured projects section
- `Skills.tsx` - Technical skill set
- `Contact.tsx` - EmailJS-integrated contact form

## 🎯 Major Components

### Navigation
- Smooth scroll side navigation bar
- Hover effects
- Indicators for sections

### Hero Section
- Dynamic typewriter effect
- Professional greeting
- Social media links
- Resume download option

### Projects
- Project cards with hover effects
- Live demo and code links
- Technology tags
- Project descriptions

### Skills
- Categorized skill display
- Animated skill tags
- Clean and modern layout

### Contact Form
- Real-time form validation
- Email integration with EmailJS
- Success/Error notifications
- Loading states

## 🎨 Styling

The portfolio employs a well-designed color scheme:
- Primary background: `#0f172a`
- Secondary background: `#1e1b4b`
- Accent color: Indigo shades
- Text colors: White and gray shades for contrast

##  🔧  Customization

1. **Colors**: Change the color scheme in `tailwind.config.js`
2. **Content**: Replace component files with your own information
3. **Styling**: Change Tailwind classes in components
4. **Animations**: Change Framer Motion parameters for various effects

## 📱 Responsive Design

- Mobile-first design
- Breakpoint-specific layouts
- Optimized for all screen sizes
- Touch-friendly interactions

## ⚡ Performance

- Optimized image loading
- Code splitting
- Lazy loading components
- Minimal dependencies

##  📄  License

MIT License - use this template for your own portfolio!

##  🤝  Contributing

Contributions, issues, and feature requests are welcome!
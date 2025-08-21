# 🌟 Foreign Jao Clone - Study Abroad Platform

A pixel-perfect clone of the Foreign Jao homepage built with modern web technologies. This project replicates the complete user experience of a study abroad consultancy platform with interactive features and responsive design.

![Foreign Jao Clone](https://img.shields.io/badge/Status-Live-brightgreen)
![React](https://img.shields.io/badge/React-18.x-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.x-cyan)

## 🚀 Live Demo

Visit the live site: `http://localhost:8081/` (when running locally)

## ✨ Features

### 🎯 Exact Foreign Jao Homepage Replica
- **"We Give You Wings"** hero section with animated gradients
- **Interactive dropdown sidebar** that appears on scroll
- **University listings** with high-quality images and detailed cards
- **Country flags** with university counts (USA, UK, Canada, Australia, etc.)
- **Student success stories** with testimonials and achievements
- **Expert consultants** section with profiles and ratings
- **Study abroad tools** (University Finder, Cost Calculator, Document Checker)
- **Blog articles** with categories and author information
- **Comprehensive footer** with newsletter signup

### 🔥 Interactive Elements
- **Smooth scroll-triggered sidebar** with dropdown navigation
- **Hover animations** on cards and buttons
- **Responsive design** that works on all devices
- **Dynamic content filtering** for universities and blog posts
- **Form interactions** for newsletter signup

### 🎨 Design System
- **Modern UI/UX** with purple-blue gradient theme
- **Consistent typography** and spacing
- **Professional iconography** using Lucide React
- **Accessible design** with proper contrast and focus states

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom components
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Server**: Express.js
- **Deployment**: Netlify-ready configuration

## 📦 Installation & Setup

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/foreign-jao-clone.git
   cd foreign-jao-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:8081/
   ```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm start` - Start production server

## 📁 Project Structure

```
vibe-haven/
├── client/                 # Frontend React application
│   ├── components/         # Reusable UI components
│   │   ├── Header.tsx      # Main navigation header
│   │   └── ui/            # Shadcn/ui components
│   ├── pages/             # Route components
│   │   ├── Index.tsx      # Homepage (Foreign Jao clone)
│   │   └── NotFound.tsx   # 404 page
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # Utility functions
│   └── global.css         # Global styles and Tailwind config
├── server/                # Backend Express server
├── public/                # Static assets
└── netlify/               # Netlify deployment functions
```

## 🎨 Key Components

### SidebarDropdownItem
Interactive dropdown component for the floating sidebar navigation.

### Hero Section
Animated hero section with "We Give You Wings" tagline and call-to-action buttons.

### University Cards
Detailed university information cards with images, rankings, and program details.

### Student Stories
Testimonial cards showcasing successful student journeys.

### Expert Consultants
Professional profiles of education consultants with ratings and specializations.

## 🌟 Key Features Implemented

### ✅ Dropdown Sidebar Navigation
- Appears on scroll past hero section
- Expandable categories (Destinations, Universities, Programs, Services, Resources)
- Smooth animations and hover effects
- Fixed positioning with proper z-index

### ✅ University Listings with Images
- High-quality university images
- Detailed information cards
- Filtering by country
- Acceptance rates and average salaries
- Popular programs display

### ✅ Responsive Design
- Mobile-first approach
- Tablet and desktop optimizations
- Flexible grid layouts
- Touch-friendly interactions

### ✅ Interactive Elements
- Hover animations
- Smooth transitions
- Button states and feedback
- Form validations

## 🎯 Performance Optimizations

- **Lazy loading** for images
- **Code splitting** with Vite
- **Optimized bundle size**
- **Fast refresh** during development
- **Production-ready builds**

## 🚀 Deployment

### Netlify (Recommended)
The project is configured for easy Netlify deployment:

1. **Connect your GitHub repository** to Netlify
2. **Build settings** are pre-configured in `netlify.toml`
3. **Deploy automatically** on every push to main branch

### Manual Deployment
```bash
npm run build
# Upload the 'dist' folder to your hosting provider
```

## 🔧 Environment Variables

Create a `.env` file in the root directory:

```env
# Add any environment variables here if needed
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is for educational purposes. All design credits go to the original Foreign Jao website.

## 🙏 Acknowledgments

- **Foreign Jao** for the original design inspiration
- **Tailwind CSS** for the utility-first styling approach
- **Lucide React** for beautiful icons
- **Shadcn/ui** for component primitives

## 📞 Contact

For any questions or feedback, please open an issue on GitHub.

---

**Made with ❤️ and modern web technologies**

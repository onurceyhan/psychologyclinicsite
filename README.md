# Uysal Psikolog Kliniği Website

A modern, warm, and child-friendly website for Uysal Psychology Clinic, specializing in play therapy for children. Built with Vue 3, Vite, and Tailwind CSS.

![Uysal Psikolog Kliniği](https://img.shields.io/badge/Vue.js-3.x-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## 🌐 Live Demo

**[View Live Site on Vercel](https://psyhologyclinicsite.vercel.app)** 🚀

Experience the website in action with full functionality and responsive design.

## ✨ Features

- **Modern & Playful Design**: Warm color palette with child-friendly illustrations and emojis
- **Responsive Layout**: Fully responsive design that works seamlessly on all devices
- **Smooth Animations**: Engaging animations and transitions for better user experience
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Accessible**: Built with accessibility best practices in mind
- **Fast Performance**: Lightning-fast load times with Vite

## 🎨 Design Philosophy

The website embodies a warm, professional, yet playful aesthetic that appeals to both parents and children:

- **Color Palette**: Sage greens and cream tones create a calming, natural atmosphere
- **Typography**: Pacifico for headings (playful) and Quicksand for body text (readable)
- **Visual Elements**: Cute emoji icons and soft gradients maintain child-friendliness
- **Photography**: High-quality stock images showing therapist-child interactions

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/onurceyhan/psychologyclinicsite.git
cd uysal-psikolog-klinigi
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The optimized production build will be in the `dist` folder.

### Preview Production Build

```bash
npm run preview
```

## 📂 Project Structure

```
psychologyclinicsite/
├── public/              # Static assets
├── src/
│   ├── components/      # Vue components
│   │   ├── Navbar.vue
│   │   ├── Hero.vue
│   │   ├── TherapySection.vue
│   │   ├── About.vue
│   │   ├── ParentGuide.vue
│   │   ├── Contact.vue
│   │   └── Footer.vue
│   ├── App.vue         # Root component
│   ├── main.js         # Application entry point
│   └── style.css       # Global styles with Tailwind
├── index.html          # HTML entry point
├── package.json        # Project dependencies
├── tailwind.config.js  # Tailwind configuration
├── vite.config.js      # Vite configuration
└── README.md           # Project documentation
```

## 🎯 Key Sections

1. **Hero Section**: Eye-catching introduction with clear call-to-action
2. **Play Therapy**: Detailed information about therapy services with cute illustrations
3. **About Us**: Build trust with professional credentials and experience
4. **Parent Guide**: Helpful tips and resources for parents
5. **Contact & Appointment**: Easy-to-use contact form and clinic information

## 🛠️ Technologies Used

- **Vue 3**: Progressive JavaScript framework for building user interfaces
- **Vite**: Next-generation frontend tooling for blazing-fast development
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Google Fonts**: Pacifico and Quicksand fonts for beautiful typography
- **Unsplash**: High-quality stock photography

## 🎨 Customization

### Colors

Edit `tailwind.config.js` to customize the color palette:

```javascript
theme: {
  extend: {
    colors: {
      sage: { /* custom sage colors */ },
      cream: { /* custom cream colors */ }
    }
  }
}
```

### Fonts

Modify the Google Fonts import in `index.html` and update `tailwind.config.js`:

```javascript
fontFamily: {
  'display': ['YourFont', 'cursive'],
  'sans': ['YourFont', 'sans-serif'],
}
```

### Content

All content can be easily modified directly in the component files within `src/components/`.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is created for Uysal Psikolog Kliniği. All rights reserved.

## 👤 Developer

**Onur Ceyhan**

- GitHub: [@onurceyhan](https://github.com/onurceyhan)
- LinkedIn: [onur-ceyhan](https://linkedin.com/in/onur-ceyhan)


# Uday Pratap Singh Bhadoriya - Portfolio Website

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS. Features a clean design with interactive elements, project filtering, and a profile picture upload system.

![Portfolio Preview](https://soft-cendol-77fa2e.netlify.app)

## 🌟 Features

### Core Functionality
- **Responsive Design** - Optimized for all device sizes from mobile to desktop
- **Smooth Scrolling Navigation** - Fixed header with active section highlighting
- **Interactive Project Filtering** - Filter projects by technology stack
- **Profile Picture Upload** - Drag & drop or browse to change profile image
- **Contact Form** - Integrated contact form with Web3Forms
- **Timeline Experience Section** - Professional timeline layout for work history

### Design Highlights
- **Modern Aesthetic** - Clean, professional design with teal and stone color palette
- **Micro-interactions** - Hover effects, transitions, and smooth animations
- **Typography** - Inter font family for excellent readability
- **Visual Hierarchy** - Clear content organization and spacing
- **Accessibility** - Semantic HTML and proper contrast ratios

## 🚀 Live Demo

Visit the live website: [https://soft-cendol-77fa2e.netlify.app](https://soft-cendol-77fa2e.netlify.app)

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **Deployment**: Netlify
- **Form Handling**: Web3Forms

## 📦 Installation & Setup

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   cd portfolio-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the website

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## 🎨 Customization

### Personal Information
Update the following files to customize with your information:

- **`src/App.tsx`** - Main content, experience, projects, and skills
- **`index.html`** - Page title and meta information

### Styling
- **`src/index.css`** - Global styles and custom CSS
- **`tailwind.config.js`** - Tailwind configuration

### Contact Form
To enable the contact form:

1. Sign up at [Web3Forms](https://web3forms.com)
2. Get your access key
3. Replace `YOUR_ACCESS_KEY_HERE` in the contact form with your actual key

## 📁 Project Structure

```
src/
├── components/
│   └── ProfilePictureUpload.tsx    # Profile picture upload modal
├── App.tsx                         # Main application component
├── main.tsx                        # Application entry point
├── index.css                       # Global styles
└── vite-env.d.ts                  # Vite type definitions

public/
└── vite.svg                       # Vite logo

Configuration files:
├── package.json                   # Dependencies and scripts
├── tsconfig.json                  # TypeScript configuration
├── tailwind.config.js            # Tailwind CSS configuration
├── vite.config.ts                # Vite build configuration
└── eslint.config.js              # ESLint configuration
```

## 🎯 Key Components

### ProfilePictureUpload
- Drag & drop image upload
- File browser integration
- Live preview functionality
- Reset to original image option

### Project Filtering
- Interactive tag-based filtering
- Smooth animations for show/hide
- Responsive grid layout

### Navigation
- Intersection Observer for active section detection
- Smooth scrolling to sections
- Fixed header with backdrop blur

## 🚀 Deployment

### Netlify (Recommended)
1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Deploy automatically on push to main branch

### Other Platforms
The project can be deployed to any static hosting service:
- Vercel
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Uday Pratap Singh Bhadoriya**
- Email: [Contact through website form](https://soft-cendol-77fa2e.netlify.app#contact)
- GitHub: [@Usthakur](https://github.com/Usthakur)
- Phone: 6266009471

---

⭐ If you found this project helpful, please give it a star on GitHub!
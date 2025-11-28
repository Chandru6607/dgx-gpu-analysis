# DGX GPU Analysis Website

A visually stunning, interactive website showcasing CUDA-based GPU optimization techniques for the NVIDIA DGX A100 system.

## 🚀 Features

- **Interactive Scrollytelling** - Animated architecture diagrams showing GPU memory hierarchy
- **Advanced Animations** - Spotlight effects and 3D tilt on hover
- **Roofline Model** - Performance methodology visualization
- **Professional Design** - Modern dark theme with NVIDIA green accents
- **Responsive Layout** - Works on all devices

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling via CDN
- **Vanilla JavaScript** - Intersection Observer API, scroll animations
- **Google Fonts** - Outfit typeface

## 📦 Deployment

### Vercel (Recommended)

1. Push this repository to GitHub
2. Visit [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Deploy! (zero configuration needed)

### Manual Deployment

Simply upload all files to any static hosting service:
- GitHub Pages
- Netlify
- AWS S3
- Any web server

## 🏃 Local Development

```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx http-server -p 8080

# Using PHP
php -S localhost:8080
```

Then open `http://localhost:8080` in your browser.

## 📁 Project Structure

```
dgx_optimization/
├── index.html           # Main website
├── comparison.html      # Scenario comparison page
├── README.md           # This file
├── vercel.json         # Vercel configuration
└── .gitignore          # Git ignore rules
```

## 🎨 Sections

1. **Hero** - Animated DGX chip visualization
2. **Uniqueness** - Hardware-software co-design approach
3. **Innovations** - Three CUDA kernel optimizations
4. **Methodology** - Roofline performance analysis
5. **Tools** - Nsight Systems and Nsight Compute

## 📝 License

Copyright © 2025 - All rights reserved

## 🤝 Contributing

Feel free to open issues or submit pull requests!

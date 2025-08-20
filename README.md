# 🌟 MAS Yasin Arafat - Portfolio Website

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=github-pages)](https://alfamas.github.io)
[![GitHub Stars](https://img.shields.io/github/stars/alfamas/alfamas.github.io?style=for-the-badge)](https://github.com/alfamas/alfamas.github.io/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/alfamas/alfamas.github.io?style=for-the-badge)](https://github.com/alfamas/alfamas.github.io/network)
[![GitHub Issues](https://img.shields.io/github/issues/alfamas/alfamas.github.io?style=for-the-badge)](https://github.com/alfamas/alfamas.github.io/issues)
[![License](https://img.shields.io/github/license/alfamas/alfamas.github.io?style=for-the-badge)](https://github.com/alfamas/alfamas.github.io/blob/main/LICENSE)

> **A modern, responsive portfolio website showcasing expertise in Travel Technology, GDS Integration, and Payment Gateway Solutions.**

![Portfolio Preview](images/portfolio-preview.png)

## 🚀 Live Demo

Visit the live website: **[alfamas.github.io/portfolio](https://alfamas.github.io)**

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Security Features](#security-features)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About

This is a professional portfolio website for **MAS Yasin Arafat**, a Travel Technology Expert specializing in:

- **GDS System Integration** (Amadeus, Sabre, Travelport)
- **Payment Gateway Solutions** (CyberSource, Multi-currency)
- **API Development** (REST, SOAP, Microservices)
- **Travel Technology** (NDC, LCC, OTA platforms)
- **Team Leadership & Management**

The website is built with modern web technologies and follows best practices for performance, security, and accessibility.

## ✨ Features

### 🎨 Design & UX

- **Responsive Design** - Perfect on all devices (mobile, tablet, desktop)
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Dark Theme** - Elegant dark color scheme with glass morphism effects
- **Interactive Elements** - Hover effects, animations, and transitions
- **Accessibility** - WCAG compliant with proper ARIA labels

### 🔧 Functionality

- **Dynamic Typing Animation** - Showcases multiple professional roles
- **Smooth Scrolling Navigation** - Single-page application with anchor links
- **Mobile-First Design** - Optimized for mobile devices
- **Contact Form Integration** - Secure form with Formspree backend
- **Social Media Links** - Centralized social link management
- **Performance Optimized** - Fast loading times and smooth animations

### 🛡️ Security Features

- **Formspree Integration** - Secure form submission without backend
- **Spam Protection** - Honeypot traps and bot detection
- **Rate Limiting** - Prevents form abuse (3 submissions/hour)
- **Input Validation** - Client-side and server-side validation
- **Privacy Compliance** - GDPR-friendly data handling
- **XSS Protection** - Sanitized inputs and secure coding practices

## 🛠️ Tech Stack

### Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Tools & Services

![Formspree](https://img.shields.io/badge/Formspree-FF6B6B?style=for-the-badge&logo=formspree&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

### Hosting

![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-181717?style=for-the-badge&logo=github&logoColor=white)

## 🚀 Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/alfamas/alfamas.github.io.git
   cd alfamas.github.io
   ```

2. **Open the project**

   ```bash
   # Open with VS Code
   code .

   # Or open index.html directly in your browser
   open index.html
   ```

3. **Customize the content**
   - Edit personal information in `index.html`
   - Replace images in the `images/` directory
   - Update social links in the JavaScript section
   - Configure Formspree for contact form

### Local Development

```bash
# If you have Python installed
python -m http.server 8000

# If you have Node.js installed
npx serve .

# If you have PHP installed
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Main HTML file
├── images/                 # Image assets
│   ├── pp1.jpg            # Hero profile image
│   ├── pp2.jpg            # About section image
│   └── portfolio-preview.png
├── README.md              # Project documentation
├── LICENSE                # License file
└── .gitignore            # Git ignore file
```

### File Details

- **`index.html`** - Single-page application with all sections
- **`images/`** - Contains profile pictures and assets
- **Inline CSS** - Custom animations and responsive design
- **Inline JavaScript** - Interactive functionality and form handling

## 🔒 Security Features

### Form Security

```javascript
// Rate limiting (3 submissions/hour)
const SECURITY_CONFIG = {
  maxSubmissions: 3,
  timeWindow: 3600000,
  rateLimit: true
};

// Honeypot spam protection
<input type="text" name="_gotcha" style="display:none">

// Input validation with regex patterns
pattern="^[a-zA-Z\s\-'\.]{2,100}$"
```

### Data Protection

- **No tracking cookies** - Privacy-first approach
- **HTTPS encryption** - Secure data transmission
- **Input sanitization** - XSS protection
- **Privacy consent** - GDPR compliance

## 🎨 Customization

### Personal Information

Update the following sections in `index.html`:

1. **Hero Section**

   ```html
   <h1>Your Name</h1>
   <p>Your professional description</p>
   ```

2. **About Section**

   ```html
   <h3>Your Title</h3>
   <p>Your detailed bio</p>
   ```

3. **Contact Information**
   ```html
   <p>your-email@domain.com</p>
   <p>Your location</p>
   ```

### Social Links

Update the `socialLinks` array in JavaScript:

```javascript
const socialLinks = [
  {
    name: "GitHub",
    url: "https://github.com/yourusername",
    icon: "fab fa-github",
  },
  // Add more social links
];
```

### Contact Form

1. **Sign up at [Formspree.io](https://formspree.io)**
2. **Create a new form** and get your form ID
3. **Update the form action**:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST"></form>
   ```

### Colors & Styling

The website uses Tailwind CSS classes. Key color schemes:

- **Primary**: Blue (`blue-600`, `blue-700`)
- **Secondary**: Purple (`purple-600`, `indigo-600`)
- **Accent**: Yellow (`yellow-400`)
- **Background**: Gray shades (`gray-50`, `gray-900`)

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Fork this repository**
2. **Go to repository Settings**
3. **Navigate to Pages section**
4. **Select source: Deploy from branch**
5. **Choose branch: main**
6. **Your site will be live at**: `https://yourusername.github.io/`

### Alternative Hosting

#### Netlify

1. **Connect your GitHub repository**
2. **Deploy automatically** on each push
3. **Custom domain** support available

#### Vercel

```bash
npm i -g vercel
vercel --prod
```

#### Traditional Web Hosting

Upload all files to your web server's public directory.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Reporting Issues

- **Bug reports** - Use the issue tracker
- **Feature requests** - Describe your idea clearly
- **Documentation** - Help improve the README

### Pull Requests

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines

- **Responsive Design** - Test on multiple devices
- **Performance** - Optimize images and code
- **Accessibility** - Follow WCAG guidelines
- **Security** - Validate all inputs
- **Code Quality** - Clean, commented code

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### MIT License Summary

- ✅ **Commercial use**
- ✅ **Modification**
- ✅ **Distribution**
- ✅ **Private use**
- ❌ **Liability**
- ❌ **Warranty**

## 📞 Contact

**MAS Yasin Arafat**

- 🌐 **Website**: [alfamas.github.io/portfolio](https://alfamas.github.io)
- 📧 **Email**: arafat0951@gmail.com
- 💼 **LinkedIn**: [linkedin.com/in/masyasinarafat](https://www.linkedin.com/in/masyasinarafat/)
- 🐙 **GitHub**: [github.com/alfamas](https://github.com/alfamas)

---

## 🌟 Show Your Support

If this project helped you, please give it a ⭐️ on GitHub!

### Share the Project

[![Twitter](https://img.shields.io/badge/Share_on-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/tweet?text=Check%20out%20this%20amazing%20portfolio%20template!&url=https://github.com/alfamas/alfamas.github.io)
[![LinkedIn](https://img.shields.io/badge/Share_on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/alfamas/alfamas.github.io)

---

<div align="center">

**Built with ❤️ by [ALFAMAS](https://github.com/alfamas)**

_Empowering the future of travel technology_

</div>

---

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/alfamas/alfamas.github.io)
![GitHub last commit](https://img.shields.io/github/last-commit/alfamas/alfamas.github.io)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/alfamas/alfamas.github.io)

## 🔄 Version History

- **v1.0.0** - Initial release with core features
- **v1.1.0** - Added security enhancements and form validation
- **v1.2.0** - Improved mobile responsiveness and animations
- **v1.3.0** - Enhanced accessibility and performance optimizations

---

_This README was last updated on August 2025_

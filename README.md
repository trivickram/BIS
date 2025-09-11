# VIT-BIS FEST 2025 🎓

![VIT-BIS FEST 2025](./public/main_poster.jpeg)

## 📋 Table of Contents
- [About](#about)
- [Event Details](#event-details)
- [Technology Stack](#technology-stack)
- [Features](#features)
- [Installation & Setup](#installation--setup)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## 🎯 About

**VIT-BIS FEST 2025** is a National Fest organized by the **School of Electronics Engineering, Vellore Institute of Technology, Chennai** in association with the **Bureau of Indian Standards (BIS)**. This comprehensive website serves as the official platform for the festival, providing information, registration facilities, and resources related to standards awareness and quality education.

### 🎪 About the Event

The VIT-BIS FEST 2025 is designed to:
- **Promote Standards Awareness**: Educate students, faculty, and industry professionals about the importance of BIS standards
- **Foster Quality Culture**: Build understanding of quality assurance and compliance in various sectors
- **Industry-Academia Collaboration**: Bridge the gap between theoretical knowledge and practical standards implementation
- **National Platform**: Provide a national stage for showcasing innovations and research in standards and quality

### 🏛️ About Bureau of Indian Standards (BIS)

The Bureau of Indian Standards (BIS) is India's national standards body, functioning under the Ministry of Consumer Affairs, Food & Public Distribution. Key aspects include:

- **Standardization**: Formulating quality and safety standards for products and services
- **Certification**: Providing ISI mark, Hallmark, and CRS certifications
- **Consumer Protection**: Ensuring product safety and reliability through compliance monitoring
- **International Trade**: Facilitating compliance with globally recognized benchmarks
- **Quality Assurance**: Conducting product testing and market surveillance

## 📅 Event Details

- **📆 Date**: March 11, 2025
- **🏢 Organized by**: School of Electronics Engineering, VIT Chennai
- **🤝 In association with**: Bureau of Indian Standards (BIS)
- **🌍 Scope**: National Level Festival
- **🎯 Focus**: Standards Awareness, Quality Education, and Industry Collaboration

## 💻 Technology Stack

### Frontend Technologies
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with animations and responsive design
- **JavaScript (ES6+)**: Interactive functionality and dynamic content
- **TailwindCSS**: Utility-first CSS framework for rapid styling
- **Flowbite**: Component library built on TailwindCSS

### Key Libraries & Frameworks
- **Flowbite Components**: Pre-built UI components
- **TailwindCSS CDN**: For responsive design and styling
- **Font Integration**: Custom typography and icons
- **Animation Libraries**: CSS animations for enhanced user experience

### Build Tools & Deployment
- **Static Website**: No build process required
- **CDN Integration**: External libraries loaded via CDN
- **Cross-browser Compatible**: Modern browser support
- **Mobile Responsive**: Optimized for all device sizes

## ✨ Features

### 🏠 Homepage
- **Event Countdown Timer**: Real-time countdown to the festival date
- **Hero Section**: Prominent display of event information and logos
- **Navigation Menu**: Responsive navigation with mobile hamburger menu
- **About BIS Section**: Comprehensive information about BIS and its importance
- **Loading Animation**: Smooth page loading experience

### 📖 Information Pages
- **About VIT**: Detailed information about Vellore Institute of Technology
- **Advisory Board**: Leadership and guidance committee details
- **Conference Speakers**: Information about keynote speakers and presenters
- **Organizing Committee**: Event organization team and patrons

### 📝 Interactive Features
- **Registration System**: Online registration for participants
- **Paper Submission**: Academic paper submission portal
- **Call for Papers**: Research paper guidelines and requirements
- **Contact Form**: Direct communication channel

### 🎨 Design Features
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional interface with intuitive navigation
- **Interactive Elements**: Hover effects, animations, and transitions
- **Accessibility**: Screen reader compatible and keyboard navigation support
- **Performance Optimized**: Fast loading times and optimized images

## 🚀 Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor or IDE (VS Code recommended)
- Local web server (optional, for development)

### Quick Start

1. **Clone the Repository**
   ```bash
   git clone https://github.com/trivickram/BIS.git
   cd BIS
   ```

2. **Open the Website**
   - **Direct Method**: Open `index.html` in your web browser
   - **Local Server Method** (Recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (if you have npx)
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the Website**
   - Direct: Open `index.html` file in browser
   - Server: Navigate to `http://localhost:8000`

### Development Setup

1. **Install VS Code Extensions** (Recommended)
   - Live Server
   - HTML CSS Support
   - TailwindCSS IntelliSense
   - Prettier Code Formatter

2. **Live Development**
   - Use Live Server extension for real-time preview
   - Enable auto-save for immediate updates
   - Use browser developer tools for debugging

## 📁 File Structure

```
BIS/
├── 📄 index.html                 # Main homepage
├── 📄 AboutVit.html             # About VIT Chennai page
├── 📄 AdvisoryBoard.html        # Advisory board information
├── 📄 CallForPapers.html        # Research paper guidelines
├── 📄 ConferenceSpeakers.html   # Speaker information
├── 📄 ContactUs.html            # Contact and communication
├── 📄 OrganizingCommittee.html  # Committee and patrons
├── 📄 PaperSubmission.html      # Paper submission portal
├── 📄 Registration.html         # Event registration
├── 📄 README.md                 # Project documentation
├── 📁 images/                   # Website images and graphics
│   ├── 🖼️ blue-vit-logo.png    # VIT Chennai logo
│   ├── 🖼️ media1.png           # Media partner logos
│   ├── 🖼️ media2.jpg           # Additional media assets
│   └── 🖼️ [other images]       # Various website images
├── 📁 logos/                    # Organization logos
│   ├── 🖼️ bis.jpeg             # BIS logo (JPEG)
│   ├── 🖼️ bis.png              # BIS logo (PNG)
│   ├── 🖼️ swc.jpeg             # SWC logo
│   └── 🖼️ [other logos]        # Partner organization logos
├── 📁 public/                   # Public assets and documents
│   ├── 🖼️ main_poster.jpeg     # Main event poster
│   ├── 📄 Registration_steps.pdf # Registration guidelines
│   ├── 📄 MEDIHACK.pdf          # Event-related documents
│   └── 📄 [other documents]     # Additional resources
└── 📁 .vscode/                  # VS Code configuration
    └── ⚙️ settings.json         # Editor settings
```

### Key Directories Explained

- **Root HTML Files**: Individual pages for different sections of the website
- **`images/`**: Contains all website graphics, logos, and visual assets
- **`logos/`**: Specific directory for organizational and partner logos
- **`public/`**: Public-facing documents, posters, and downloadable resources
- **`.vscode/`**: Development environment configuration

## 🖥️ Usage

### For Visitors

1. **Browse Event Information**
   - Visit homepage for event overview and countdown
   - Navigate through different sections using the menu
   - Download resources from the public folder

2. **Registration Process**
   - Click on "Registration" in the navigation menu
   - Follow the step-by-step registration process
   - Refer to `Registration_steps.pdf` for detailed guidelines

3. **Academic Participation**
   - Check "Call for Papers" for submission guidelines
   - Use "Paper Submission" portal for academic contributions
   - Review speaker information and conference details

### For Developers

1. **Customization**
   - Modify HTML files for content updates
   - Update styling using TailwindCSS classes
   - Add new pages following the existing structure

2. **Content Updates**
   - Update event dates in JavaScript countdown timer
   - Modify contact information in ContactUs.html
   - Update speaker and committee information as needed

3. **Adding New Features**
   - Integrate new TailwindCSS components
   - Add interactive JavaScript functionality
   - Include additional Flowbite components

## 🤝 Contributing

We welcome contributions to improve the VIT-BIS FEST 2025 website! Here's how you can contribute:

### Getting Started

1. **Fork the Repository**
   ```bash
   git clone https://github.com/yourusername/BIS.git
   cd BIS
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow existing code style and structure
   - Test your changes across different browsers
   - Ensure responsive design principles

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add: Brief description of your changes"
   ```

5. **Push and Create Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

### Contribution Guidelines

- **Code Quality**: Follow HTML5 semantics and accessibility standards
- **Responsive Design**: Ensure all changes work on mobile and desktop
- **Performance**: Optimize images and minimize external dependencies
- **Documentation**: Update README.md for significant changes
- **Testing**: Test across multiple browsers and devices

### Areas for Contribution

- 🎨 **UI/UX Improvements**: Enhanced design and user experience
- 📱 **Mobile Optimization**: Better mobile responsiveness
- ♿ **Accessibility**: Improved accessibility features
- ⚡ **Performance**: Page load optimization
- 🌐 **Internationalization**: Multi-language support
- 🔧 **Functionality**: New features and interactive elements

## 📞 Contact

### Event Organizers
- **Institution**: Vellore Institute of Technology, Chennai
- **Department**: School of Electronics Engineering
- **Website**: [VIT Chennai](https://chennai.vit.ac.in/)

### Technical Support
- **Repository**: [GitHub - trivickram/BIS](https://github.com/trivickram/BIS)
- **Issues**: Please report bugs and feature requests via GitHub Issues
- **Documentation**: Refer to this README for setup and usage guidelines

### Partnership Inquiries
- **Bureau of Indian Standards**: Official partner for the festival
- **Media Partnerships**: Contact through the website's contact form
- **Academic Collaboration**: Reach out via institutional channels

## 📄 License

This project is created for educational and promotional purposes for the VIT-BIS FEST 2025. 

### Usage Rights
- ✅ **Educational Use**: Free to use for educational and learning purposes
- ✅ **Non-commercial**: Personal and academic use permitted
- ✅ **Modification**: Can be modified for similar educational events
- ❌ **Commercial Use**: Commercial usage requires permission
- ❌ **Redistribution**: Do not redistribute without attribution

### Attribution
- **Design & Development**: VIT Chennai Team
- **Content**: Bureau of Indian Standards & VIT Chennai
- **Frameworks**: TailwindCSS, Flowbite
- **Repository**: GitHub - trivickram/BIS

---

## 🙏 Acknowledgments

- **VIT Chennai**: For organizing and hosting the festival
- **Bureau of Indian Standards**: For partnership and content guidance
- **TailwindCSS & Flowbite**: For the excellent UI framework and components
- **Open Source Community**: For the tools and libraries that made this project possible

---

<div align="center">

**🎓 VIT-BIS FEST 2025 - Promoting Standards Awareness & Quality Education 🎓**

Made with ❤️ by VIT Chennai Team

[🌐 Visit Website](./index.html) | [📧 Contact Us](./ContactUs.html) | [📝 Register](./Registration.html)

</div>
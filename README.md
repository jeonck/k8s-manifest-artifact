# Kubernetes Manifest Artifact

A modern web application for generating and managing Kubernetes manifest files, built with Vite + React + Tailwind CSS.

## 🌐 Live Demo

**Access the application**: [https://1102680.github.io/k8s-manifest-artifact/](https://1102680.github.io/k8s-manifest-artifact/)

## 📋 Project Description

This tool provides an intuitive web interface for creating Kubernetes manifest files. Whether you're deploying applications, configuring services, or managing resources, this application simplifies the process of generating properly formatted YAML manifests.

### Key Features
- Interactive form-based manifest generation
- Support for common Kubernetes resources (Deployments, Services, ConfigMaps, etc.)
- Real-time YAML preview
- Download generated manifests
- Modern, responsive UI with Tailwind CSS
- Automated deployment via GitHub Pages

## 🚀 Technology Stack

- **Frontend**: React 18 with modern hooks
- **Build Tool**: Vite for fast development and optimized builds
- **Styling**: Tailwind CSS for responsive design
- **Deployment**: GitHub Pages with automated CI/CD
- **Package Manager**: npm with lock file for reproducible builds

## 🛠 Development

### Prerequisites
- Node.js 18+
- npm

### Local Development
```bash
# Clone the repository
git clone https://github.com/1102680/k8s-manifest-artifact.git
cd k8s-manifest-artifact

# Install dependencies
cd react-app
npm install

# Start development server
npm run dev
# Application available at http://localhost:5173

# Build for production
npm run build

# Preview production build
npm run preview
# Production preview at http://localhost:4173/k8s-manifest-artifact/
```

### Project Structure
```
k8s-manifest-artifact/
├── .github/workflows/deploy.yml    # Automated deployment
├── react-app/                      # Main application
│   ├── src/
│   │   ├── App.jsx                 # Main component
│   │   ├── main.jsx                # Entry point
│   │   └── index.css               # Styles
│   ├── public/vite.svg             # Assets
│   ├── vite.config.js              # Build configuration
│   └── package.json                # Dependencies
└── README.md                       # This file
```

## 🚢 Deployment

The application is automatically deployed to GitHub Pages when changes are pushed to the main branch:

1. **Automatic**: Push to `main` branch triggers GitHub Actions
2. **Manual**: Use GitHub Actions "Deploy to GitHub Pages" workflow
3. **Local Testing**: Run `npm run preview` to test production build

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- **Live Application**: [https://1102680.github.io/k8s-manifest-artifact/](https://1102680.github.io/k8s-manifest-artifact/)
- **Repository**: [https://github.com/1102680/k8s-manifest-artifact](https://github.com/1102680/k8s-manifest-artifact)
- **Issues**: [https://github.com/1102680/k8s-manifest-artifact/issues](https://github.com/1102680/k8s-manifest-artifact/issues)
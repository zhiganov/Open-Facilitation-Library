# Open Facilitation Library (OFL)

An open-source initiative to democratize facilitation wisdom and enhance collective sensemaking capabilities through machine-readable patterns and AI integration.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 🎯 Project Overview

OFL turns facilitation wisdom into machine-readable patterns and workflows while building a comprehensive data lake for reinforcement learning of AI agents. The library is designed to serve as shared infrastructure for Metagov projects and AI-powered deliberative tools.

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- MongoDB 5.0+
- Python 3.9+ (for ML components)

### Installation

```bash
git clone https://github.com/yourusername/open-facilitation-library.git
cd open-facilitation-library
npm install
```

### Environment Setup

```bash
cp .env.example .env
# Edit .env with your configuration
```

### Running Locally

```bash
npm run dev
```

Visit `http://localhost:3000`

### Deployment

1. **Docker Deployment**
   ```bash
   docker-compose up -d
   ```

2. **Manual Deployment**
   ```bash
   npm run build
   npm start
   ```

3. **Cloud Deployment**
   - Follow our [Cloud Deployment Guide](docs/deployment.md)
   - Supported platforms: Vercel, Railway, Heroku

## 🔧 Forking & Customization

1. Fork the repository
2. Update `config/default.json` with your settings
3. Modify patterns in `data/patterns/`
4. Update API endpoints in `src/api/`

See [Customization Guide](docs/customization.md) for detailed instructions.

## 🐛 Bug Reports

1. Check if the issue already exists in [Issues](https://github.com/yourusername/open-facilitation-library/issues)
2. Use our bug report template
3. Include:
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Environment details
   - Screenshots if applicable

## ✨ Feature Requests

1. Check existing [Feature Requests](https://github.com/yourusername/open-facilitation-library/labels/enhancement)
2. Use our feature request template
3. Include:
   - Use case
   - Expected benefits
   - Proposed implementation
   - Alternative solutions considered

## 👥 Contributing

We love your input! See our [Contributing Guide](CONTRIBUTING.md) for details on:

- Code of Conduct
- Development process
- Pull Request process
- Coding standards
- Testing requirements

### Getting Started

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🏆 Top Contributors

- [Name](https://github.com/username) - Core Maintainer
- [Name](https://github.com/username) - Pattern Library Lead
- [Name](https://github.com/username) - ML Infrastructure

## 🤝 Partners

### Technical Partners
- Harmonica
- Talk to the City
- Metagov

### Domain Experts
- International Association of Facilitators
- Institute of Cultural Affairs
- CoCap

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Support Us

If you find this project useful, please consider:
- Starring the repository
- Contributing patterns or code
- Supporting us through [Giveth](https://giveth.io/project/open-facilitation-library)

---

*Part of the Metagov Interoperable Deliberative Tools Programme*

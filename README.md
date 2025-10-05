# Channel Living - Hugo PaperMod Website

Welcome to Channel Living, a lifestyle blog focused on home & living, healthy lifestyle, smart living, and daily inspiration.

## 🏠 About

Channel Living is your go-to destination for:
- **Home & Living**: Interior design tips, home organization, and creating comfortable living spaces
- **Healthy Lifestyle**: Wellness tips, healthy recipes, and lifestyle advice
- **Smart Living**: Technology integration, productivity tips, and modern living solutions
- **Daily Inspiration**: Motivational content and positive lifestyle changes

## 🚀 Technology Stack

- **Hugo**: Static site generator
- **PaperMod Theme**: Clean and modern Hugo theme
- **GitHub Pages**: Hosting platform
- **GitHub Actions**: Automated deployment

## 📁 Project Structure

```
channelliving/
├── content/
│   ├── posts/          # Blog posts
│   ├── about.md        # About page
│   └── archives.md     # Archives page
├── static/
│   ├── favicon/        # Favicon files
│   └── assets/images/  # Images and media
├── themes/PaperMod/    # Hugo theme (submodule)
├── .github/workflows/  # GitHub Actions
└── hugo.toml          # Hugo configuration
```

## 🛠️ Local Development

### Prerequisites
- Hugo Extended v0.146.0 or higher
- Git

### Setup
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd channelliving
   ```

2. Initialize submodules:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server
   ```

4. Open your browser and visit `http://localhost:1313`

## 📝 Creating Content

### New Blog Post
```bash
hugo new posts/your-post-title.md
```

### Post Frontmatter Example
```yaml
---
title: "Your Post Title"
date: 2024-01-15T10:00:00+07:00
tags: ["lifestyle", "home-living"]
categories: ["Lifestyle"]
author: "Channel Living Team"
description: "Brief description of your post"
cover:
    image: "/assets/images/your-image.jpg"
    alt: "Image description"
    caption: "Image caption"
draft: false
---
```

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. Every push to the `main` branch triggers a new deployment.

### Manual Deployment
```bash
hugo --minify
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

- Website: [Channel Living](https://your-domain.com)
- Instagram: [@channelliving](https://instagram.com/channelliving)
- YouTube: [Channel Living](https://youtube.com/@channelliving)
- GitHub: [Channel Living](https://github.com/channelliving)

---

Built with ❤️ using Hugo and PaperMod theme
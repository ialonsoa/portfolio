# Product Management Portfolio

This repository contains a professional portfolio website built with Quarto that automatically publishes to GitHub Pages.

## 🚀 Getting Started

### Quick Setup
1. **Update your information** in the following files:
   - `index.qmd` - Replace "Your Name" and update your bio, skills, and contact links
   - `about.qmd` - Add your background, education, experience, and career goals

2. **Add your profile image**:
   - Add a professional headshot to the `images/` folder named `profile.jpg`
   - Update image paths in `index.qmd` and `about.qmd` if you use a different filename

3. **Customize your projects**:
   - Replace the content in `projects/project-1.qmd`, `projects/project-2.qmd`, etc.
   - Add project images to the `images/` folder
   - Update project titles and descriptions in `_quarto.yml`

4. **Commit and push** your changes - your website will automatically be published!

## 📁 File Structure

```
├── .github/workflows/publish.yml    # Automatic deployment to GitHub Pages
├── _quarto.yml                      # Website configuration
├── index.qmd                        # Homepage
├── about.qmd                        # About page
├── projects/                        # Your project showcases
│   ├── project-1.qmd
│   ├── project-2.qmd
│   └── project-3.qmd
├── images/                          # Photos and project images
└── README.md                        # This file
```

## ✨ Features

- **Automatic Deployment**: Push to main branch → website updates automatically
- **Professional Design**: Clean, modern layout perfect for sharing with employers
- **Mobile Responsive**: Looks great on all devices
- **SEO Friendly**: Optimized for search engines and social media sharing

## 🎨 Customization

### Adding New Projects
1. Create a new `.qmd` file in the `projects/` folder
2. Add the project to the navigation menu in `_quarto.yml`
3. Link to it from your homepage in `index.qmd`

### Changing the Theme
Update the theme in `_quarto.yml`:
```yaml
format:
  html:
    theme: [cosmo, flatly, litera, minty, pulse, sandstone, simplex, sketchy, slate, solar, spacelab, superhero, united, yeti]
```

### Custom Styling
- Add custom CSS in a `styles.css` file
- Reference it in `_quarto.yml` under `format: html: css: styles.css`

## 🌐 Your Live Website

Once you push your changes, your portfolio will be available at:
`https://[your-username].github.io/[repository-name]/`

You can find this URL in your repository settings under "Pages" or in the Actions tab after deployment completes.

## 🆘 Need Help?

- **Quarto Documentation**: https://quarto.org/docs/websites/
- **Markdown Guide**: https://www.markdownguide.org/basic-syntax/
- **GitHub Pages**: https://docs.github.com/en/pages

## 📄 License

This template is available under the MIT License. Feel free to use it for your own portfolio!

---

**Ready to showcase your work? Start by updating `index.qmd` with your information!**
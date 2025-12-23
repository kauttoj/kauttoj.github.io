# Janne Kauttonen - Personal Portfolio Website

A professional portfolio website showcasing research, publications, and projects in AI, data science, and neuroscience.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **About Section**: Professional background and expertise
- **Resume**: Education, experience, and skills
- **Publications**: Tabbed view separating peer-reviewed and non-peer-reviewed publications
- **Projects**: Showcase of GitHub repositories and research projects
- **Contact**: Multiple contact methods and location map

## Quick Start

### Option 1: Local Development

1. Open `index.html` in your web browser
2. The website will work immediately with placeholder images

### Option 2: GitHub Pages Hosting

1. Create a new repository named `yourusername.github.io` (replace with your GitHub username)
2. Upload all files to this repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" and choose "main" branch
5. Your site will be live at `https://yourusername.github.io`

## Customization

### Replace Placeholder Images

1. Add your professional photo as `assets/images/my-avatar.png` (recommended: 150x150px)
2. Add project images or keep the placeholder
3. Add a favicon as `assets/images/logo.ico`

### Update Content

All content is in `index.html`. Key sections to customize:

- **About**: Lines 115-150 (update your bio)
- **Resume**: Lines 250-450 (add/edit education and experience)
- **Publications**: Lines 550-850 (update with your publications)
- **Projects**: Lines 950-1100 (add your projects)
- **Contact**: Lines 1150-1250 (verify contact information)

### Colors and Styling

Edit `assets/css/style.css` to change colors. Key color variables are at the top of the file (lines 8-45).

## Current Content

The portfolio currently includes:

- **About**: Bio from LinkedIn profile
- **Core Expertise**: 6 main areas (AI, Complex Systems, Neuroscience, Programming, Research Leadership, Consulting)
- **Experience**: Senior Researcher at Haaga-Helia, Postdoc positions at Aalto/CMU, Researcher at Laurea
- **Education**: PhD in Statistical Physics
- **Publications**: Top peer-reviewed papers and project reports
- **Projects**: 5 GitHub repositories + GAIK project description
- **Contact Info**: 
  - Email: janne.kauttonen@haaga-helia.fi
  - GitHub: github.com/kauttoj
  - LinkedIn: linkedin.com/in/jkauttonen
  - Google Scholar: TqrL-c8AAAAJ
  - ORCID: 0000-0003-2432-5072

## File Structure

```
janne-portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # Stylesheet
│   ├── js/
│   │   └── script.js      # Interactive features
│   └── images/
│       ├── my-avatar.png  # Your photo
│       ├── project-placeholder.jpg
│       └── logo.ico       # Favicon (optional)
├── README.md              # This file
└── create_placeholders.py # Script to generate placeholder images
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, animations, and flexbox/grid
- **JavaScript**: Vanilla JS for interactivity
- **Ion Icons**: Icon library
- **Google Fonts**: Poppins font family

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Feel free to use this template for your own portfolio. Attribution appreciated but not required.

## Credits

Template design inspired by vCard by codewithsadee
Content and customization by Claude (Anthropic)

## Next Steps

1. Replace placeholder images with your actual photos
2. Review and update all content sections
3. Test on different devices and browsers
4. Deploy to GitHub Pages or your preferred hosting
5. Share your portfolio URL!

## Need Help?

For questions about:
- **Content**: Review the research information sources used
- **Technical issues**: Check browser console for errors
- **Customization**: Refer to inline comments in HTML/CSS files

---

**Last Updated**: December 2024
**Version**: 1.0

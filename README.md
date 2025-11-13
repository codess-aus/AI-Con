# AI-Con

Resources for AI-Con Talk - A modern, accessible, responsive website exploring AI, responsibility, and innovation.

## Features

- 🎨 **Beautiful Design**: Modern gradient theme from cyan to dusty purple
- 🌓 **Light/Dark Mode**: Seamless switching between themes for comfortable reading
- 📱 **Responsive**: Perfect viewing experience on any device
- ♿ **Accessible**: Built following accessibility best practices
- 🖼️ **Hero Images**: Eye-catching hero images on every page
- 🔍 **Searchable**: Built-in search functionality
- 🚀 **Fast**: Static site generation for optimal performance

## Chapters

1. **Home** - Introduction to AI-Con
2. **The AI Shift** - Understanding how AI is transforming industries and society
3. **Responsible AI** - Ethical considerations and best practices
4. **Trust** - Building and maintaining trust in AI systems
5. **Risks** - Identifying potential challenges and pitfalls
6. **Mitigation** - Strategies to address AI-related risks
7. **Prompt Engineering** - Mastering the art of communicating with AI
8. **Microsoft Copilot** - Leveraging AI in your Microsoft workflow
9. **GitHub Copilot** - Enhancing development with AI assistance
10. **Contact** - Get in touch and join the conversation

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/codess-aus/AI-Con.git
cd AI-Con
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Building the Site

To build the static site:

```bash
mkdocs build
```

This will create a `site/` directory with the generated HTML files.

### Running Locally

To run the development server:

```bash
mkdocs serve
```

Then open your browser and navigate to `http://127.0.0.1:8000`

The development server includes live reload, so any changes you make to the documentation will automatically refresh in your browser.

### Building for Production

To build the site with strict mode (fails on warnings):

```bash
mkdocs build --strict
```

## Project Structure

```
AI-Con/
├── docs/                   # Documentation source files
│   ├── index.md           # Home page
│   ├── ai-shift.md        # The AI Shift chapter
│   ├── responsible-ai.md  # Responsible AI chapter
│   ├── trust.md           # Trust chapter
│   ├── risks.md           # Risks chapter
│   ├── mitigation.md      # Mitigation chapter
│   ├── prompt-engineering.md   # Prompt Engineering chapter
│   ├── microsoft-copilot.md    # Microsoft Copilot chapter
│   ├── github-copilot.md      # GitHub Copilot chapter
│   ├── contact.md         # Contact page
│   ├── images/            # Hero images for each page
│   └── stylesheets/       # Custom CSS
│       └── extra.css      # Gradient and theme customization
├── mkdocs.yml             # MkDocs configuration
├── requirements.txt       # Python dependencies
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## Customization

### Theme Colors

The gradient colors are defined in `docs/stylesheets/extra.css`:

```css
:root {
  --gradient-start: #00bcd4; /* cyan */
  --gradient-end: #9575cd;   /* dusty purple */
}
```

### Navigation

Update the navigation structure in `mkdocs.yml` under the `nav:` section.

### Hero Images

Hero images are located in `docs/images/` and are referenced in each page using:

```markdown
<div class="hero-container">
  <img src="images/page-name.png" alt="Page Title" class="hero-image">
</div>
```

## Technologies Used

- **MkDocs**: Static site generator
- **Material for MkDocs**: Modern, responsive theme
- **Python**: Programming language
- **Markdown**: Content format
- **CSS**: Custom styling

## Deployment

### GitHub Pages

To deploy to GitHub Pages:

```bash
mkdocs gh-deploy
```

This command builds the site and pushes it to the `gh-pages` branch.

### Other Platforms

The `site/` directory contains static HTML files that can be deployed to any web hosting platform:

- Netlify
- Vercel
- AWS S3
- Azure Static Web Apps
- And many more...

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [MkDocs](https://www.mkdocs.org/)
- Theme by [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- Inspired by the AI community

## Contact

Visit the [Contact page](https://codess-aus.github.io/AI-Con/contact/) for more information on how to get in touch.

---

Made with ❤️ for the AI-Con community

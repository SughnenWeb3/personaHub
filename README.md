# PersonaHub

A modern profile page project showcasing team members and services with a clean, responsive design built with Tailwind CSS.

`Tech Stack`

**HTML5** - Semantic markup and structure
**Tailwind CSS v4.2.2** - Utility-first CSS framework for styling
**Node.js** - Package management and build tools

📁  `Project Structure`

```
personaHub/
├── index.html          # Main landing page
├── team.html           # Team members page
├── services.html       # Services page
├── contact.html        # Contact page
├── [member].html       # Individual profile pages
├── src/
│   ├── input.css       # Tailwind CSS imports
│   └── output.css      # Compiled CSS styles
├── package.json        # Project dependencies
└── README.md           # This file
```

## 🛠️ Installation & Setup

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Clone the Repository

```bash
git clone git@github.com:SughnenWeb3/personaHub.git
cd personaHub
```

### Install Dependencies

```bash
npm install
```

### Development

The project uses Tailwind CSS for styling. The CSS is already compiled in `src/output.css`, but if you need to make changes:

1. Modify styles in `src/input.css`
2. Compile using Tailwind CLI:

```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### Running the Project

This is a static HTML project. Simply open any HTML file in your browser, or use a live server extension in your code editor for development with auto-reload.

## 📄 Pages Overview

- **index.html** - Main landing page with overview
- **team.html** - Team members showcase
- **services.html** - Services offered
- **contact.html** - Contact information and form
- **Individual profiles** - Personal pages for each team member

## 🎨 Customization

### Styling

The project uses Tailwind CSS. `src/output.css` is the compiled production file and should not be modified directly.

To customize styles:
1. Edit `src/input.css` for custom styles
2. Compile to update `src/output.css`:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```
3. Modify HTML classes in individual files

### Adding New Team Members

1. Create a new HTML file (e.g., `newmember.html`)
2. Follow the existing template structure
3. Update `team.html` to include the new member

## 🚀 Deployment

This project is designed for Vercel deployment:

1. **Vercel (Recommended)**: 
   - Connect your GitHub repository to Vercel
   - Vercel will automatically detect and deploy the static site
   - Zero configuration needed

2. **Alternative Static Hosting**:
   - Netlify: Drag and drop the project folder
   - GitHub Pages: Enable in repository settings

## 📝 License

This project is licensed under the ISC License.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

**Built with ❤️ using Tailwind CSS**

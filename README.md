# evansnursingstudy.github.io
# NursingStudyHub - Nursing Education & Research Platform

A comprehensive platform for nursing students to access study materials, conduct research, and master evidence-based practice through interactive case studies and resources.

## Features

- **Study Materials**: Comprehensive nursing textbooks, study guides, and educational resources
- **Case Studies**: Interactive real-world patient cases and nursing care scenarios
- **Research Tools**: Research methodology guides, statistical tools, and citation generators
- **Reference Library**: Quick access to medical journals, nursing databases, and evidence-based practice resources

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nursing-study-hub.git
   cd nursing-study-hub
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Building for Production

To build the application for production:

```bash
npm run build
```

This will create a `dist` directory with the optimized production build.

## Deployment

### GitHub Pages Deployment

This project is configured for automatic deployment to GitHub Pages:

1. **Create a GitHub repository** for this project
2. **Push your code** to the repository:
   ```bash
   git remote add origin https://github.com/your-username/nursing-study-hub.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click Settings > Pages
   - Under Source, select "Deploy from a branch"
   - Select "main" branch
   - Click "Save"

4. **Your site will be live at**: `https://your-username.github.io/nursing-study-hub`

### Manual Deployment

You can also deploy manually:

```bash
npm run deploy
```

## Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page components
│   ├── Home.tsx       # Home page
│   ├── CaseStudies.tsx # Case studies page
│   └── StudyMaterials.tsx # Study materials page
├── App.tsx            # Main app component
├── main.tsx           # Entry point
└── shadcn.css         # Global styles

scripts/
└── build.mjs          # Build script

.github/
└── workflows/
    └── deploy.yml      # GitHub Actions deployment

dist/                  # Build output (created during build)
```

## Technologies Used

- **React 18** - Frontend framework
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Icon library
- **React Router** - Client-side routing
- **ESBuild** - Fast bundler
- **GitHub Actions** - CI/CD

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue in the GitHub repository or contact the development team.

---

**Note**: This project is designed for educational purposes and demonstrates best practices in React development, TypeScript, and modern web technologies.

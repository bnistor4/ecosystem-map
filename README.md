# MultiversX Ecosystem Map

A comprehensive visual map showcasing the entire MultiversX ecosystem, featuring projects across DeFi, NFTs, Gaming, AI, Tools, and more. Built by xAlliance to provide the community with a centralized view of all projects building on MultiversX.

## 🌟 Features

- **Interactive Visual Map**: Beautiful masonry layout displaying ecosystem projects
- **Animated Galaxy Background**: Stunning 3D animated galaxy using Three.js
- **Category Organization**: Projects organized into 11 categories:
  - DeFi (Decentralized Finance)
  - Tools & Utilities
  - AI & Machine Learning
  - NFT Marketplaces
  - NFTs & Collections
  - Gaming
  - Startups
  - Memes
  - Development Resources
  - Media & Community
  - Staking Agencies

- **Screenshot Export**: Take and download screenshots of the ecosystem map
- **Responsive Design**: Optimized for desktop and mobile devices
- **Real-time Updates**: Easy submission system for project updates

## 🚀 How It Works

The MultiversX Ecosystem Map is a React-based web application that:

1. **Displays Projects**: Renders project cards in a responsive masonry layout
2. **Categorizes Content**: Groups projects by their primary function or industry
3. **Visual Appeal**: Features an animated 3D galaxy background for immersive experience
4. **Community Driven**: Allows community members to submit new projects or updates
5. **Export Functionality**: Enables users to capture and share the ecosystem state

### Technology Stack

- **Frontend**: React 19 with TypeScript
- **Styling**: Bootstrap 5 + Sass
- **3D Graphics**: Three.js with React Three Fiber
- **Build Tool**: Vite
- **Icons**: FontAwesome
- **Layout**: React Masonry Component

## 🛠️ Installation & Setup

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn package manager

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ecosystem-map.git
   cd ecosystem-map
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173` to view the application

### Available Scripts

- `npm run dev` - Start development server
- `npm run dev-expose` - Start development server accessible from network
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🎯 How to Use

### Viewing the Ecosystem

1. **Browse Categories**: Scroll through different project categories
2. **Click Projects**: Visit project websites by clicking on project cards
3. **Take Screenshots**: Use the settings menu (gear icon) to export PNG screenshots
4. **Responsive Navigation**: The layout automatically adjusts to your screen size

### Settings Menu

Access the floating settings menu (gear icon) to:
- **Submit Updates**: Add new projects or update existing ones
- **Take Screenshots**: Export the current view as a PNG image

## 🤝 How to Participate

### Adding Your Project

1. **Submit via Form**: Click the "Submit an update" button in the settings menu
2. **Fill Required Information**:
   - Project name
   - Website URL
   - Project category
   - Logo/icon (preferably SVG or high-quality PNG)
   - Brief description

3. **Review Process**: Submissions are reviewed by the xAlliance team
4. **Integration**: Approved projects are added to the next update

### Contributing to Development

1. **Fork the Repository**
   ```bash
   git fork https://github.com/your-username/ecosystem-map.git
   ```

2. **Create Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**
   - Add new features
   - Fix bugs
   - Improve documentation
   - Optimize performance

4. **Submit Pull Request**
   - Ensure code follows project standards
   - Include clear description of changes
   - Test thoroughly before submission

### Project Structure for Contributors

```
src/
├── components/          # React components
│   ├── Category.tsx     # Category display component
│   ├── Project.tsx      # Individual project card
│   ├── Galaxy.tsx       # 3D animated background
│   └── ...
├── config/
│   ├── categories.tsx   # Category definitions
│   ├── projects.tsx     # Project data
│   └── general.tsx      # General configuration
├── types/               # TypeScript type definitions
└── assets/              # Static assets and logos
```

### Adding New Projects (Developers)

1. **Add Project Data**: Edit `src/config/projects.tsx`
   ```typescript
   {
       category: Category.defi,
       name: 'Your Project',
       url: 'https://yourproject.com',
       icon: '/logos/yourproject.svg',
   }
   ```

2. **Add Logo**: Place logo file in `public/logos/` directory
3. **Test Locally**: Verify the project appears correctly
4. **Submit PR**: Create pull request with your changes

### Guidelines for Contributions

- **Code Quality**: Follow TypeScript best practices
- **Performance**: Optimize images and minimize bundle size
- **Accessibility**: Ensure components are accessible
- **Documentation**: Update README for significant changes
- **Testing**: Test across different browsers and devices

## 📝 Project Categories

| Category | Description |
|----------|-------------|
| DeFi | Decentralized finance protocols and applications |
| Tools | Utilities, explorers, and development tools |
| AI | Artificial intelligence and machine learning projects |
| Marketplaces | NFT and digital asset marketplaces |
| NFTs | NFT collections and related projects |
| Gaming | Blockchain games and gaming platforms |
| Startups | Early-stage projects and incubators |
| Memes | Community-driven meme projects |
| Development | Developer resources and documentation |
| Media | Community media and content platforms |
| Staking | Staking providers and delegation services |

## 🔧 Configuration

### Environment Variables

Create a `.env` file for local development:
```env
VITE_API_URL=your_api_url_here
```

### Customization

- **Colors**: Modify Bootstrap variables in Sass files
- **Categories**: Update `src/config/categories.tsx`
- **Projects**: Edit `src/config/projects.tsx`
- **Styling**: Customize components in `src/components/`

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **xAlliance**: Project creators and maintainers
- **MultiversX Community**: For building an amazing ecosystem
- **Contributors**: Everyone who helps improve the map

## 📞 Support

- **Issues**: Report bugs via GitHub Issues
- **Updates**: Submit via the in-app form
- **Community**: Join xAlliance Discord for discussions

---

**Built with ❤️ by xAlliance for the MultiversX Community**

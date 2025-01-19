# Riwayat - Indian Cultural Heritage Platform

A modern web application showcasing India's rich cultural heritage through an interactive platform that connects artisans, cultural enthusiasts, and learners.

## Features

- **Interactive Cultural Map**: Explore cultural events and activities across different regions of India
- **Artisan Marketplace**: Browse and purchase authentic handcrafted products directly from artisans
- **Creator Hub**: Platform for artists and cultural practitioners to share their work
- **Learning Modules**: Access to workshops and educational content about traditional arts
- **Community Engagement**: Connect with other cultural enthusiasts and practitioners

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Lucide React Icons

## Prerequisites

Before running this project, make sure you have:

- Node.js (v16 or higher)
- npm (v7 or higher)

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd riwayat
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and visit `http://localhost:5173`

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Creates a production build
- `npm run preview` - Previews the production build locally
- `npm run lint` - Runs ESLint to check code quality

## Deployment

The application is deployed on Netlify. You can:

1. Create a production build:
   ```bash
   npm run build
   ```

2. Deploy the contents of the `dist` folder to your hosting provider

## Project Structure

```
src/
├── components/         # React components
│   ├── AuthModal.tsx  # Authentication modal
│   ├── Header.tsx     # Main navigation header
│   ├── ImageCarousel.tsx  # Hero section carousel
│   ├── InteractiveMap.tsx # Cultural map component
│   ├── Marketplace.tsx    # Artisan marketplace
│   └── QuickAccessCard.tsx # Navigation cards
├── App.tsx            # Main application component
├── main.tsx          # Application entry point
└── index.css         # Global styles
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Images sourced from Unsplash
- Icons provided by Lucide React

# Modern Pizza Restaurant Website 🍕

A modern, responsive website for a pizza restaurant featuring an interactive menu, location information, and business hours. Built with React and styled using Tailwind CSS.

## Features

- 📱 Responsive design that works on mobile, tablet, and desktop
- 🍽️ Interactive menu with beautiful food presentation
- 📍 Location information with business hours
- 🎨 Modern UI with smooth animations
- 💅 Custom styled components using shadcn/ui

## Technologies Used

- React
- TypeScript
- Tailwind CSS
- shadcn/ui components
- Wouter for routing
- React Query for data management
- Zod for type validation

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to the local server address shown in the console

## Project Structure

```
├── src/
│   ├── components/      # Reusable UI components
│   ├── hooks/          # Custom React hooks
│   ├── lib/            # Utility functions and configurations
│   ├── pages/          # Page components
│   └── App.tsx         # Main application component
├── public/             # Static assets
└── index.html          # HTML entry point
```

## Pages

- **Home**: Landing page with hero section and featured items
- **Menu**: Complete menu with categories and items
- **Location**: Restaurant location and business hours

## Customization

The website uses a theme configuration in `theme.json` for consistent styling. You can modify:
- Primary colors
- Theme variant (professional/tint/vibrant)
- Border radius
- Light/dark mode preferences

## Building for Production

To create a production build:

1. Run the build command:
   ```bash
   npm run build
   ```
2. The built files will be in the `dist` directory
3. Deploy these files to your web hosting service

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

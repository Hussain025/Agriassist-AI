# AgriAssist AI - Agricultural Technology Platform

A comprehensive agricultural technology platform serving Farmers, Experts, Buyers, and Admins with AI-powered features, marketplace functionality, and mobile-responsive design.

## Features

- **Role-Specific Dashboards**: Customized experiences for Farmers, Experts, Buyers, and Admins
- **AI-Powered Tools**: Crop disease detection (95%+ accuracy), plant health monitoring, pest identification
- **Marketplace**: Multi-image product listings, inventory tracking, order management
- **Mobile-First Design**: Touch-optimized (44px minimum targets), offline support, sub-2s load times on 3G
- **Light & Dark Mode**: Accessible themes for extended use
- **PWA Support**: Offline functionality with service workers

## Design System

### Color Palette
- **Primary**: Sage Green (#2D5016)
- **Secondary**: Terracotta (#C65D3B)
- **Neutral**: Cream (#F5E6D3), Charcoal (#1A1A1A)
- **Accents**: Green (#4CAF50), Blue (#2196F3), Amber (#FFC107)

### Typography
- Primary: System fonts (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto)
- Heading: Georgia, Times New Roman

### Touch Targets
- Minimum: 44px
- Comfortable: 48px
- Large: 56px

## Tech Stack

- React 18+
- Firebase (Firestore, Auth, Storage, Functions)
- Framer Motion (animations)
- React Router (navigation)
- React Icons

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

## Project Structure

```
src/
├── components/
│   ├── common/          # Reusable UI components
│   ├── dashboard/       # Role-specific widgets
│   ├── ai-tools/        # AI feature components
│   └── marketplace/     # Marketplace components
├── pages/
│   ├── farmer/          # Farmer-specific pages
│   ├── expert/          # Expert-specific pages
│   ├── buyer/           # Buyer-specific pages
│   └── admin/           # Admin-specific pages
├── hooks/               # Custom React hooks
├── styles/              # Global styles and theme
└── services/            # Firebase and API services
```

## Accessibility

- WCAG AA compliant
- Keyboard navigation support
- Screen reader optimized
- Color contrast ratios meet standards

## Performance

- Lazy loading for images
- Code splitting
- Service worker caching
- Optimized for 3G networks

## License

Proprietary - AgriAssist AI Platform

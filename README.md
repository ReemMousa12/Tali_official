# Tali

A cutting-edge event discovery and ticketing platform for live entertainment and music events.

## Overview

Tali is a modern, responsive platform dedicated to showcasing and promoting live entertainment events, particularly focused on the Cairo music and events scene. The platform provides a seamless experience for event discovery, artist information, event scheduling, ticket booking, and community engagement. Built with modern web technologies, Tali connects event enthusiasts with top-tier artists and venues, offering an intuitive interface to explore upcoming events, browse artist galleries, and manage bookings.

## Features

- **Event Discovery**: Browse upcoming events with detailed information, artist lineups, and venue details
- **Event Scheduling**: View comprehensive event calendars with dates, times, and booking information
- **Artist Profiles**: Explore artist information and event history
- **Gallery**: Visual showcases of past events and artist performances
- **Ticketing Integration**: Direct booking links to event ticketing platforms
- **Partner Showcase**: Display of featured venues and event partners
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Dynamic Hero Sections**: Eye-catching animated video backgrounds with artist spotlights

## Tech Stack

- **Frontend Framework**: React 18.3
- **Language**: TypeScript
- **Build Tool**: Vite
- **CSS Framework**: Tailwind CSS
- **Component Library**: shadcn/ui
- **Form Management**: React Hook Form
- **State Management**: TanStack React Query
- **Routing**: React Router v6
- **Icons**: Lucide React & React Icons
- **Charts**: Recharts
- **Styling Utilities**: clsx, tailwind-merge

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Available Scripts

- **Development**: `npm run dev` - Start the development server
- **Build**: `npm run build` - Build for production
- **Build (Dev)**: `npm run build:dev` - Build in development mode
- **Preview**: `npm run preview` - Preview production build
- **Lint**: `npm run lint` - Run ESLint

## Project Structure

```
src/
├── pages/           # Page components (Index, About, Solutions, etc.)
├── components/      # Reusable UI components
├── lib/            # Utility functions and helpers
├── hooks/          # Custom React hooks
├── assets/         # Static assets
├── App.tsx         # Main App component
├── main.tsx        # Entry point
└── index.css       # Global styles
```

## Pages

- **Home** (`/`) - Landing page featuring hero section with animated videos, upcoming events carousel, event schedule, and partner showcase
- **About** (`/about`) - Information about Tali, mission, and platform details
- **Solutions** (`/solutions`) - Features and solutions offered by the platform with floating animations
- **Events** (`/events`) - Dedicated events page with detailed listings and booking information
- **Gallery** (`/gallery`) - Visual gallery showcasing past events and artist performances
- **Contact** (`/contact-page`) - Contact form and communication channel for inquiries and partnerships

## Development

To start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the port shown in your terminal).

## Build & Deployment

To create a production build:

```bash
npm run build
```

The built files will be in the `dist/` directory, which can be deployed to any static hosting service.

## Key Components

### Layout Components
- **Header** - Responsive navigation bar with site links and branding
- **Footer** - Footer section with contact information and links
- **Hero Sections** - Dynamic hero components with video backgrounds and animations

### Content Sections
- **EventsSection** - Displays upcoming events with artist information and booking links
- **ScheduleSection** - Event calendar and scheduling information
- **PartnersSection** - Showcase of featured venues and event partners
- **Gallery** - Visual media gallery for event and artist photos
- **AboutSection** - Platform information and mission details
- **SolutionsSection** - Features and offerings with visual elements
- **FeaturesSection** - Detailed feature descriptions

### UI Components
- Built using shadcn/ui library with Radix UI primitives
- Customizable buttons, dialogs, tooltips, and form components
- Theme support with next-themes integration

## Events Featured

Tali showcases events from renowned artists and venues including:
- Electronic music events
- Live performances and DJ sets
- Festival lineups
- Special showcase events
- Collaborations and special occasions



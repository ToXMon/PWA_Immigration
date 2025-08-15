# PWA Immigration - Citizenship Prep App

A Progressive Web Application designed to help users prepare for citizenship tests and immigration processes.

## Features

- **Practice Mode**: Interactive question practice with immediate feedback
- **Review Mode**: Comprehensive review of previously answered questions
- **Audio Support**: Text-to-speech functionality for accessibility
- **Progressive Web App**: Works offline and can be installed on devices

## Tech Stack

- **Framework**: Next.js 14.2.3
- **Language**: TypeScript
- **State Management**: Zustand
- **Styling**: CSS Modules
- **Audio**: Web Speech API integration

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   npm run export
   ```

4. Serve the static build:
   ```bash
   npm start
   ```

## Project Structure

- `app/` - Next.js app directory with pages and components
- `data/` - Question data and content
- `lib/` - Utility functions and helpers
- `public/` - Static assets and PWA manifest

## PWA Features

This app includes:
- Service worker for offline functionality
- Web app manifest for installation
- Responsive design for all devices

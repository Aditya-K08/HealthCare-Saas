# HealthSync Dashboard - Healthcare SaaS UI

HealthSync is a premium B2B Healthcare SaaS platform designed for healthcare professionals to manage patients, analyze trends, and receive real-time alerts. This application demonstrates advanced frontend development skills using a modern React architecture.

## 🚀 Features

- **🛡️ Secure Authentication**: Managed sessions with Zustand and simulated Firebase Auth.
- **📊 Advanced Analytics**: Interactive data visualization using Recharts for recovery trends and admissions.
- **👥 Patient Management**: Dynamic Grid and List views with real-time search and status monitoring.
- **🔔 Real-time Notifications**: Integrated Service Worker for critical medical push notifications.
- **🎨 Premium Design System**: 100% Vanilla CSS with a focus on glassmorphism, responsiveness, and micro-animations.

## 🛠️ Tech Stack

- **Framework**: React 18+ (with Vite)
- **Language**: TypeScript
- **State Management**: Zustand
- **Styling**: Vanilla CSS (Custom Variables-based Design System)
- **Charts**: Recharts
- **Icons**: Lucide React
- **Notifications**: Service Worker API

## 📋 Getting Started

### Prerequisites

- Node.js (v16.0 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya-K08/HealthCare-Saas.git
   cd healthcare-saas-ui
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## 🔐 Credentials

For demonstration purposes, use the following credentials to log in:
- **Email**: `admin@healthcare.com`
- **Password**: `password`

## 📁 Directory Structure

```text
src/
├── components/   # Reusable UI and Layout components
├── features/     # Feature-specific logic
├── hooks/        # Custom React hooks (e.g., useServiceWorker)
├── layouts/      # Application page layouts
├── lib/          # External service configurations (Firebase)
├── pages/        # Top-level route components
├── services/     # Mock data and API simulations
├── store/        # Zustand state definitions
└── styles/       # Global CSS variables and base styles
```

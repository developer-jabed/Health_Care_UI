# 🏥 HealthCare UI - Modern Telemedicine Platform

<div align="center">

![HealthCare UI Banner](https://img.shields.io/badge/HealthCare-UI_Platform-blue?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-38B2AC?style=flat-square&logo=tailwind-css)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-0.8-000000?style=flat-square)

**AI-powered healthcare platform with seamless doctor matching and telemedicine services**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Active-success?style=for-the-badge)](https://health-care-ui-sepia.vercel.app/)
[![GitHub Repo](https://img.shields.io/badge/📂_GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/developer-jabed/Health_Care_UI.git)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</div>

## 🌐 Quick Links

<div align="center">

| Platform | Link | Status |
|----------|------|--------|
| **🌍 Live Application** | [https://health-care-ui-sepia.vercel.app/](https://health-care-ui-sepia.vercel.app/) | ✅ Active |
| **📦 GitHub Repository** | [https://github.com/developer-jabed/Health_Care_UI.git](https://github.com/developer-jabed/Health_Care_UI.git) | 🔗 Source |
| **⚙️ Backend API** | [https://health-care-backend-o0cj.onrender.com](https://health-care-backend-o0cj.onrender.com) | 🔗 API |

</div>

---

## 📋 Table of Contents
- [✨ Features](#-features)
- [🚀 Tech Stack](#-tech-stack)
- [🏗 Architecture](#-architecture)
- [🎨 UI/UX Design](#uiux-design)
- [📱 Pages & Components](#-pages--components)
- [⚙️ Installation](#️-installation)
- [🔧 Configuration](#-configuration)
- [🎯 Key Features Deep Dive](#-key-features-deep-dive)
- [🧪 Testing](#-testing)
- [🚀 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Features

### 🎯 **AI-Powered Doctor Matching**
- ✅ **Smart Symptom Analysis** - AI algorithms analyze symptoms and medical history
- ✅ **Personalized Recommendations** - Matches patients with ideal doctors based on multiple factors
- ✅ **Specialty Filtering** - Intelligent filtering across 10+ medical specialties
- ✅ **Rating & Review Integration** - Considers doctor ratings and patient feedback

### 👤 **Patient Experience**
- ✅ **Intuitive Dashboard** - Personalized health dashboard with metrics
- ✅ **Easy Doctor Search** - Advanced search with filters and sorting
- ✅ **Appointment Booking** - One-click appointment scheduling
- ✅ **Video Consultations** - Integrated WebRTC video calling
- ✅ **Digital Prescriptions** - View and manage electronic prescriptions
- ✅ **Health Records** - Secure access to medical history
- ✅ **Review System** - Rate and review healthcare providers

### 🩺 **Doctor Portal**
- ✅ **Professional Profile** - Complete doctor profile management
- ✅ **Appointment Calendar** - Interactive calendar for scheduling
- ✅ **Patient Management** - Access to patient records (with consent)
- ✅ **Prescription Writer** - Digital prescription generation
- ✅ **Video Consultation Room** - Integrated video call interface
- ✅ **Earnings Dashboard** - Track consultations and payments

### 🔧 **Platform Features**
- ✅ **Responsive Design** - Mobile-first, fully responsive interface
- ✅ **Real-time Updates** - Live notifications and status updates
- ✅ **Secure Authentication** - JWT-based auth with role-based access
- ✅ **Payment Integration** - Stripe-powered payment processing
- ✅ **Multi-language Support** - Internationalization ready
- ✅ **Accessibility** - WCAG 2.1 compliant components
- ✅ **Performance Optimized** - Fast loading with code splitting

---

## 🚀 Tech Stack

<div align="center">

### **Core Framework**
| Technology | Purpose | Version |
|------------|---------|---------|
| ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) | React Framework & SSR | 14.x |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) | Type Safety & Development | 5.x |
| ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) | UI Library | 18.x |

### **Styling & UI Components**
| Technology | Purpose | Version |
|------------|---------|---------|
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) | Utility-First CSS | 3.3.x |
| ![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?logo=shadcnui&logoColor=white) | Component Library | 0.8.x |
| ![Lucide Icons](https://img.shields.io/badge/Lucide_Icons-000000?logo=lucide&logoColor=white) | Icon Library | 0.3.x |
| ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?logo=framer&logoColor=white) | Animations | 10.x |

### **State & Data Management**
| Technology | Purpose |
|------------|---------|
| ![React Query](https://img.shields.io/badge/React_Query-FF4154?logo=reactquery&logoColor=white) | Server State Management |
| ![Zustand](https://img.shields.io/badge/Zustand-000000?logo=zustand&logoColor=white) | Client State Management |
| ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?logo=reacthookform&logoColor=white) | Form Management |
| ![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white) | Schema Validation |

### **External Integrations**
| Technology | Purpose |
|------------|---------|
| ![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white) | Payment Processing |
| ![Socket.io](https://img.shields.io/badge/Socket.io-010101?logo=socket.io&logoColor=white) | Real-time Communication |
| ![WebRTC](https://img.shields.io/badge/WebRTC-333333?logo=webrtc&logoColor=white) | Video Calling |
| ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white) | Data Visualization |

### **Development Tools**
| Technology | Purpose |
|------------|---------|
| ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint&logoColor=white) | Code Linting |
| ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?logo=prettier&logoColor=black) | Code Formatting |
| ![Husky](https://img.shields.io/badge/Husky-000000?logo=husky&logoColor=white) | Git Hooks |
| ![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white) | Testing Framework |

</div>

---

## 🏗 Architecture

```mermaid
graph TB
    subgraph "Presentation Layer"
        A1[Next.js Pages]
        A2[React Components]
        A3[shadcn/ui Components]
        A4[Tailwind Styling]
    end
    
    subgraph "Application Layer"
        B1[React Context/State]
        B2[React Query Hooks]
        B3[Custom Hooks]
        B4[Form Management]
    end
    
    subgraph "Services Layer"
        C1[API Service]
        C2[Auth Service]
        C3[Payment Service]
        C4[Video Call Service]
        C5[Notification Service]
    end
    
    subgraph "Integration Layer"
        D1[Backend API]
        D2[Stripe API]
        D3[WebRTC Servers]
        D4[Socket.io Server]
    end
    
    A1 --> B1
    A2 --> B2
    A3 --> B3
    B1 --> C1
    B2 --> C2
    B3 --> C3
    C1 --> D1
    C2 --> D1
    C3 --> D2
    C4 --> D3
🎨 UI/UX Design
Design System
Color Palette: Healthcare-focused (Blues, Greens, Neutrals)

Primary: #2563eb (Trust Blue)

Secondary: #10b981 (Health Green)

Background: #f8fafc (Light Gray)

Text: #1e293b (Dark Slate)

Typography: Inter font family with proper hierarchy

Spacing: 8px baseline grid system

Border Radius: Consistent 0.375rem (6px)

Shadows: Subtle shadows for depth (shadow-sm, shadow-md)

Responsive Breakpoints
css
/* Tailwind Defaults */
sm: 640px   /* Small devices */
md: 768px   /* Tablets */
lg: 1024px  /* Laptops */
xl: 1280px  /* Desktops */
2xl: 1536px /* Large screens */
Component Library (shadcn/ui)
Buttons: Primary, Secondary, Outline, Ghost variants

Cards: Patient cards, Doctor profiles, Appointment cards

Forms: Validation, error states, loading states

Modals: Appointment booking, prescription view

Tables: Patient lists, appointment history

Navigation: Sidebar, top navigation, breadcrumbs

📱 Pages & Components
Core Pages
Page	Route	Description
Homepage	/	AI-powered doctor finder & platform overview
Doctor Search	/doctors	Advanced doctor search with filters
Doctor Profile	/doctors/[id]	Detailed doctor information & booking
Patient Dashboard	/dashboard	Patient health dashboard & appointments
Doctor Dashboard	/doctor/dashboard	Doctor portal & appointment management
Appointment Booking	/appointment/book	Schedule new appointment
Video Consultation	/consultation/[id]	Live video call interface
Prescriptions	/prescriptions	Digital prescriptions management
Health Records	/health-records	Medical history & records
Admin Panel	/admin	Platform administration
Key Components
typescript
// Example component structure
components/
├── ui/                    # shadcn/ui components
│   ├── button.tsx
│   ├── card.tsx
│   └── dialog.tsx
├── layout/               # Layout components
│   ├── Header.tsx
│   ├── Sidebar.tsx
│   └── Footer.tsx
├── doctors/              # Doctor-related components
│   ├── DoctorCard.tsx
│   ├── DoctorSearch.tsx
│   └── DoctorProfile.tsx
├── appointments/         # Appointment components
│   ├── AppointmentCard.tsx
│   ├── BookingForm.tsx
│   └── CalendarView.tsx
├── video/               # Video call components
│   ├── VideoRoom.tsx
│   ├── VideoControls.tsx
│   └── ParticipantView.tsx
└── shared/              # Shared components
    ├── LoadingSpinner.tsx
    ├── ErrorBoundary.tsx
    └── Notification.tsx
⚙️ Installation
Prerequisites
Node.js 18+ installed

npm, yarn, or pnpm package manager

Git for version control

Step-by-Step Setup
Clone the repository

bash
git clone https://github.com/developer-jabed/Health_Care_UI.git
cd Health_Care_UI
Install dependencies

bash
# Using npm
npm install

# Using yarn
yarn install

# Using pnpm
pnpm install
Set up environment variables

bash
cp .env.example .env.local
# Edit .env.local with your configuration
Run the development server

bash
# Development mode
npm run dev
# or
yarn dev
# or
pnpm dev
Open in browser
Navigate to http://localhost:3000

Docker Setup (Alternative)
bash
# Build and run with Docker
docker build -t healthcare-ui .
docker run -p 3000:3000 healthcare-ui

# Using Docker Compose
docker-compose up --build
🔧 Configuration
Environment Variables (.env.local)
env
# Next.js Configuration
NEXT_PUBLIC_API_URL=https://health-care-backend-o0cj.onrender.com/api/v1
NEXT_PUBLIC_APP_URL=https://health-care-ui-sepia.vercel.app
NEXT_PUBLIC_APP_NAME="HealthCare UI"

# Authentication
NEXT_PUBLIC_JWT_SECRET=your_jwt_secret_here
NEXT_PUBLIC_REFRESH_TOKEN_SECRET=your_refresh_secret_here

# Stripe Configuration
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=pk_test_your_publishable_key
STRIPE_SECRET_KEY=sk_test_your_secret_key
NEXT_PUBLIC_STRIPE_SUCCESS_URL=/payment/success
NEXT_PUBLIC_STRIPE_CANCEL_URL=/payment/cancel

# Video Calling
NEXT_PUBLIC_VIDEO_API_KEY=your_video_api_key
NEXT_PUBLIC_VIDEO_SECRET=your_video_secret
NEXT_PUBLIC_TURN_SERVER_URL=your_turn_server_url

# Feature Flags
NEXT_PUBLIC_ENABLE_VIDEO_CALLS=true
NEXT_PUBLIC_ENABLE_AI_MATCHING=true
NEXT_PUBLIC_ENABLE_PAYMENTS=true

# Analytics (Optional)
NEXT_PUBLIC_GOOGLE_ANALYTICS_ID=GA_MEASUREMENT_ID
NEXT_PUBLIC_HOTJAR_ID=your_hotjar_id
Tailwind Configuration
javascript
// tailwind.config.js
module.exports = {
  darkMode: ["class"],
  content: [
    './pages/**/*.{ts,tsx}',
    './components/**/*.{ts,tsx}',
    './app/**/*.{ts,tsx}',
    './src/**/*.{ts,tsx}',
  ],
  theme: {
    container: {
      center: true,
      padding: "2rem",
      screens: {
        "2xl": "1400px",
      },
    },
    extend: {
      colors: {
        border: "hsl(var(--border))",
        input: "hsl(var(--input))",
        ring: "hsl(var(--ring))",
        background: "hsl(var(--background))",
        foreground: "hsl(var(--foreground))",
        primary: {
          DEFAULT: "hsl(var(--primary))",
          foreground: "hsl(var(--primary-foreground))",
        },
        secondary: {
          DEFAULT: "hsl(var(--secondary))",
          foreground: "hsl(var(--secondary-foreground))",
        },
        // Healthcare specific colors
        healthcare: {
          blue: "#2563eb",
          green: "#10b981",
          teal: "#0d9488",
          orange: "#f97316",
        },
      },
    },
  },
  plugins: [require("tailwindcss-animate")],
}
Setting up shadcn/ui
bash
# Initialize shadcn/ui
npx shadcn-ui@latest init

# Add components as needed
npx shadcn-ui@latest add button
npx shadcn-ui@latest add card
npx shadcn-ui@latest add dialog
npx shadcn-ui@latest add form
# ... add more components
🎯 Key Features Deep Dive
AI-Powered Doctor Finder
typescript
// Example AI matching logic
interface PatientProfile {
  symptoms: string[];
  medicalHistory: string[];
  preferences: {
    specialty?: string;
    genderPreference?: string;
    location?: string;
    language?: string;
  };
}

interface DoctorProfile {
  specialty: string;
  experience: number;
  rating: number;
  availability: Availability[];
  languages: string[];
  location: string;
}

const findMatchingDoctors = (
  patient: PatientProfile, 
  doctors: DoctorProfile[]
): DoctorProfile[] => {
  return doctors
    .filter(doctor => 
      // Specialty match
      doctor.specialty === patient.preferences.specialty ||
      // Symptom-based matching
      matchesSymptoms(patient.symptoms, doctor.specialty)
    )
    .sort((a, b) => {
      // Weighted scoring algorithm
      const scoreA = calculateMatchScore(patient, a);
      const scoreB = calculateMatchScore(patient, b);
      return scoreB - scoreA;
    });
};
Real-time Video Consultation
WebRTC Integration: Peer-to-peer video calling

Screen Sharing: Option to share screen during consultation

Chat Functionality: In-call text chat

Recording: Optional session recording (with consent)

Virtual Background: Professional background options

Network Optimization: Adaptive bitrate for poor connections

Appointment Booking Flow
🧪 Testing
Test Setup
bash
# Install testing dependencies
npm install --save-dev jest @testing-library/react @testing-library/jest-dom

# Run tests
npm test
# or
npm run test:watch
Example Test
typescript
// __tests__/DoctorCard.test.tsx
import { render, screen } from '@testing-library/react';
import { DoctorCard } from '../components/doctors/DoctorCard';

describe('DoctorCard', () => {
  const mockDoctor = {
    id: '1',
    name: 'Dr. Cameron Williamson',
    specialty: 'Cardiologist',
    rating: 4.9,
    reviews: 23,
    image: '/doctors/dr-cameron.jpg',
    isAiRecommended: true,
  };

  it('renders doctor information correctly', () => {
    render(<DoctorCard doctor={mockDoctor} />);
    
    expect(screen.getByText('Dr. Cameron Williamson')).toBeInTheDocument();
    expect(screen.getByText('Cardiologist')).toBeInTheDocument();
    expect(screen.getByText('4.9')).toBeInTheDocument();
    expect(screen.getByText('(23 reviews)')).toBeInTheDocument();
  });

  it('shows AI recommended badge when applicable', () => {
    render(<DoctorCard doctor={mockDoctor} />);
    expect(screen.getByText('✨ AI Recommended Specialist')).toBeInTheDocument();
  });
});
Testing Strategies
Unit Tests: Component testing with Jest & React Testing Library

Integration Tests: API integration and flow testing

E2E Tests: Cypress for complete user journey testing

Performance Tests: Lighthouse CI for performance monitoring

Accessibility Tests: axe-core for accessibility compliance

🚀 Deployment
Vercel Deployment (Recommended)
Connect to Vercel

Push code to GitHub repository

Import project in Vercel dashboard

Configure build settings automatically

Vercel Configuration

json
// vercel.json
{
  "buildCommand": "npm run build",
  "devCommand": "npm run dev",
  "installCommand": "npm install",
  "framework": "nextjs",
  "outputDirectory": ".next",
  "regions": ["iad1"],
  "env": {
    "NEXT_PUBLIC_API_URL": "https://health-care-backend-o0cj.onrender.com/api/v1"
  }
}
Environment Variables in Vercel

Go to Project Settings → Environment Variables

Add all variables from .env.local

Redeploy after adding variables

Alternative Deployment Options
Netlify
toml
# netlify.toml
[build]
  command = "npm run build"
  publish = ".next"

[build.environment]
  NEXT_PUBLIC_API_URL = "https://health-care-backend-o0cj.onrender.com/api/v1"

[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200
AWS Amplify
yaml
# amplify.yml
version: 1
frontend:
  phases:
    preBuild:
      commands:
        - npm ci
    build:
      commands:
        - npm run build
  artifacts:
    baseDirectory: .next
    files:
      - '**/*'
  cache:
    paths:
      - node_modules/**/*
Self-hosted (Docker)
dockerfile
# Dockerfile
FROM node:18-alpine AS base

# Install dependencies
FROM base AS deps
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm ci

# Build application
FROM base AS builder
WORKDIR /app
COPY --from=deps /app/node_modules ./node_modules
COPY . .
RUN npm run build

# Production image
FROM base AS runner
WORKDIR /app
ENV NODE_ENV production
COPY --from=builder /app/public ./public
COPY --from=builder /app/.next ./.next
COPY --from=builder /app/node_modules ./node_modules
COPY --from=builder /app/package.json ./package.json
EXPOSE 3000
CMD ["npm", "start"]
Performance Optimization
javascript
// next.config.js
/** @type {import('next').NextConfig} */
const nextConfig = {
  reactStrictMode: true,
  swcMinify: true,
  images: {
    domains: ['health-care-backend-o0cj.onrender.com', 'localhost'],
    formats: ['image/avif', 'image/webp'],
  },
  compress: true,
  poweredByHeader: false,
  generateEtags: true,
  i18n: {
    locales: ['en', 'es', 'fr'],
    defaultLocale: 'en',
  },
  async headers() {
    return [
      {
        source: '/(.*)',
        headers: [
          {
            key: 'X-DNS-Prefetch-Control',
            value: 'on'
          },
          {
            key: 'Strict-Transport-Security',
            value: 'max-age=63072000; includeSubDomains; preload'
          },
          {
            key: 'X-Content-Type-Options',
            value: 'nosniff'
          },
        ],
      },
    ];
  },
};

module.exports = nextConfig;
🤝 Contributing
We welcome contributions from the community! Here's how you can help:

Development Workflow
Fork the repository

Create a feature branch

bash
git checkout -b feature/amazing-feature
Make your changes

Run tests and linting

bash
npm run test
npm run lint
Commit with conventional commits

bash
git commit -m "feat: add amazing feature"
Push to your fork

bash
git push origin feature/amazing-feature
Open a Pull Request

Commit Convention
feat: New feature

fix: Bug fix

docs: Documentation changes

style: Code formatting

refactor: Code restructuring

test: Adding or updating tests

chore: Maintenance tasks

perf: Performance improvements

ci: CI/CD changes

Code Quality Standards
Use TypeScript for type safety

Follow ESLint configuration

Write meaningful comments for complex logic

Add tests for new features

Update documentation when needed

Follow responsive design principles

Ensure accessibility compliance

Pull Request Checklist
Code follows project conventions

Tests pass successfully

No TypeScript errors

Responsive design tested

Accessibility considerations

Documentation updated

No console errors/warnings

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

📞 Support & Contact
For support, questions, or feedback:

GitHub Issues: Create an issue

Email: jabed@example.com (Update with your contact)

Live Chat: Available on the website

Documentation: API Docs

🙏 Acknowledgments
Next.js Team - For the amazing React framework

shadcn/ui - For beautiful, accessible components

Tailwind CSS - For utility-first CSS framework

Vercel - For seamless deployment

All Contributors - For making this project better

<div align="center">
Built with ❤️ for better healthcare accessibility
Star this repo if you found it useful! ⭐

https://img.shields.io/github/stars/developer-jabed/Health_Care_UI?style=social
https://img.shields.io/github/forks/developer-jabed/Health_Care_UI?style=social

Visit the Live Application: https://health-care-ui-sepia.vercel.app/

</div>
Last Updated: October 2024
Version: 1.0.0
Next.js: 14.x
React: 18.x

text

## 📥 How to Use This README

### **Quick Setup Instructions:**

1. **Save the file:**
   ```bash
   # In your Health_Care_UI project folder
   echo 'PASTE_THE_CONTENT_ABOVE' > README.md
Customize for your project:

Update email addresses

Add your specific API endpoints

Include your actual feature list

Add screenshots from your application

Add to your repository:

bash
git add README.md
git commit -m "docs: add professional README documentation"
git push origin main
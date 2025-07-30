#  Travel Planner App

A modern full-stack travel planning application built using **Vite + React**, **Appwrite**, **Stripe**, **Syncfusion**, and more. Users can register, log in, and plan trips with rich interactive maps, AI travel suggestions, payments, and stunning destinations.

---

## Features

-  **Authentication** via Appwrite
-  **Trip Management** (create, update, delete)
-  **Interactive Maps** with Syncfusion
-  **Stripe Payments** for premium features
-  **AI Suggestions** powered by Gemini API
-  Beautiful travel destination images using Unsplash API

---

##  Tech Stack

| Tech          | Purpose                      |
|---------------|------------------------------|
| Vite + React  | Frontend Framework           |
| Tailwind CSS  | Styling                      |
| Appwrite      | Auth & Database              |
| Syncfusion    | Maps & UI Components         |
| Stripe        | Payments                     |
| Unsplash API  | Travel images                |
| Gemini API    | AI-powered itinerary helper  |

---



##  Project Structure
```text
.
├── app
│   ├── appwrite
│   │   ├── auth.ts
│   │   ├── client.ts
│   │   ├── dashboard.ts
│   │   └── trips.ts
│   ├── constants
│   │   ├── index.ts
│   │   └── world_map.ts
│   ├── lib
│   │   ├── stripe.ts
│   │   └── utils.ts
│   └── routes
│       ├── admin
│       │   ├── admin-layout.tsx
│       │   ├── all-users.tsx
│       │   ├── create-trip.tsx
│       │   ├── dashboard.tsx
│       │   ├── trip-detail.tsx
│       │   └── trips.tsx
│       ├── api
│       │   └── create-trip.ts
│       └── root
│           ├── page-layout.tsx
│           ├── payment-success.tsx
│           ├── sign-in.tsx
│           └── travel-detail.tsx
├── components
│   ├── Header.tsx
│   ├── InfoPill.tsx
│   ├── MobileSidebar.tsx
│   ├── NavItems.tsx
│   ├── RootNavbar.tsx
│   ├── StatsCard.tsx
│   └── TripCard.tsx
├── public
├── styles
│   └── app.css
├── .dockerignore
├── .env.local
├── .gitignore
├── Dockerfile
├── index.d.ts
├── react-router.config.ts
├── root.tsx
├── routes.ts
├── package.json
├── package-lock.json
├── tsconfig.json
├── vite.config.ts
└── README.md


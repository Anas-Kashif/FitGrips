<div align="center">

# FitGrips

**High-Performance Fitness Gear and Apparel E-Commerce Platform**

An end-to-end modern web storefront tailored for powerlifters and athletes. Built with Next.js 16, React 19, Tailwind CSS v4, and Redux Toolkit.

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16.0-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-19.0-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-State-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux Toolkit" />
  <img src="https://img.shields.io/badge/Vercel-Deployment-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>

</div>

---

## Overview

FitGrips is a dedicated digital storefront delivering premium weightlifting accessories, including lifting belts, grips, ankle straps, and workout essentials. The platform combines server-side rendering for optimal performance with persistent client-side state for shopping and authentication flows.

---

## Key Features

| Capability | Details |
| :--- | :--- |
| **Product Showcase** | Dynamic catalog navigation, category filtering, and slug-based product pages. |
| **Persistent Cart** | Client-side cart state managed with Redux Toolkit and preserved via Redux Persist. |
| **User Authentication** | Account authentication routes, referral program, and session management. |
| **Editorial & Community** | Built-in blog section, customer FAQs, and order fulfillment guides. |
| **Responsive Interface** | Clean, mobile-first design styled with Tailwind CSS and Lucide icons. |

---

## Technology Stack

| Category | Technology | Logo / Badge |
| :--- | :--- | :--- |
| **Framework** | Next.js 16 (App Router) | <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js" /> |
| **Library** | React 19 | <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React" /> |
| **Styling** | Tailwind CSS v4 | <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind" /> |
| **Icons** | Lucide React | <img src="https://img.shields.io/badge/Lucide-F56565?style=flat&logo=lucide&logoColor=white" alt="Lucide" /> |
| **State Management** | Redux Toolkit & Persist | <img src="https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white" alt="Redux" /> |
| **Networking** | Axios | <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white" alt="Axios" /> |
| **Feedback UI** | React Hot Toast | <img src="https://img.shields.io/badge/HotToast-FFA500?style=flat&logo=react&logoColor=white" alt="React Hot Toast" /> |

---

## Project Structure

```text
fitgrips/
├── app/                  # Next.js App Router (pages and layouts)
│   ├── [slug]/           # Dynamic product details
│   ├── auth/             # Sign-in and registration pages
│   ├── blogs/            # Fitness articles and editorial content
│   ├── cart/             # Shopping cart and checkout review
│   ├── shop/             # Product catalog
│   ├── layout.js         # Root layout with font and Redux providers
│   └── page.js           # Homepage
├── components/           # Reusable UI modules (Navbar, Footer, Home)
├── public/               # Static assets, fonts, and images
├── next.config.mjs       # Next.js configuration
├── package.json          # Dependencies and npm scripts
└── postcss.config.mjs    # PostCSS pipeline for Tailwind CSS
```

---

## Getting Started

### Prerequisites

Ensure [Node.js](https://nodejs.org) (v18 or higher) is installed on your system.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Anas-Kashif/FitGrips.git
   cd FitGrips
   ```

2. **Install project dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server:**
   ```bash
   npm run dev
   ```

4. **Access the application:**
   Open [http://localhost:3000](http://localhost:3000) in your web browser.

---

## Available Scripts

| Command | Purpose |
| :--- | :--- |
| `npm run dev` | Runs the Next.js development server with hot-reloading |
| `npm run build` | Compiles the production build |
| `npm run start` | Starts the production server |
| `npm run lint` | Runs ESLint code quality checks |

---

## License

This project is licensed under the MIT License.

---

<div align="center">
  <sub>Developed by <strong>Anas</strong></sub>
  <br />
  <br />
  <a href="https://github.com/Anas-Kashif">
    <img src="https://img.shields.io/badge/GitHub-Anas--Kashif-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub - Anas-Kashif" />
  </a>
</div>

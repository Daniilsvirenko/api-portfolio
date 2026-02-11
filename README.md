# 🚀 API-First Developer Portfolio

> A unique developer portfolio designed to mimic high-end API documentation. Built with Next.js, Tailwind CSS, and Framer Motion.


## ✨ Features

- **Terminal Hero Section**: Realistic typing animation that "fetches" user data.
- **API Documentation Style**: Navigation and content structured as API endpoints (GET /experience, POST /contact).
- **Interactive JSON Responses**: Experience and projects are presented as beautiful, syntax-highlighted JSON payloads.
- **"Deep Dark" Theme**: A premium dark mode aesthetic (`#0B0C10`) with neon accents.
- **Responsive Design**: Fully responsive sidebar (drawer on mobile) and layout.
- **AI Chat Widget**: A floating chat assistant (mock) for added interactivity.

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Syntax Highlighting**: [react-syntax-highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter)

## 🚀 Getting Started

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Daniilsvirenko/api-portfolio.git
    cd api-portfolio
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Run the development server**
    ```bash
    npm run dev
    ```

4.  Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📂 Project Structure

```
├── app/
│   ├── layout.tsx       # Root layout with fonts and theme
│   └── page.tsx         # Main single-page application logic
├── components/
│   ├── Sidebar.tsx      # Navigation (Endpoints list)
│   ├── Hero.tsx         # Terminal typing effect
│   ├── ApiEndpoint.tsx  # Collapsible accordion for sections
│   ├── JsonViewer.tsx   # Syntax highlighted JSON display
│   ├── SkillsGrid.tsx   # Visual grid for skills
│   └── ChatWidget.tsx   # Floating AI assistant
├── lib/
│   └── data.ts          # Centralized content file (CV data)
└── public/              # Static assets
```

## 🎨 Customization

To personalize this portfolio, simply edit the `lib/data.ts` file. All content (profile, experience, projects, skills) is dynamically rendered from this single source of truth.

```typescript
// lib/data.ts
export const portfolioData = {
  personal: {
    name: "Your Name",
    role: "Your Role",
    // ...
  },
  // ...
};
```

This project is open source and available under the [MIT License](LICENSE).

---
*Built with ❤️ by [Daniil Svirenko](https://github.com/Daniilsvirenko)*

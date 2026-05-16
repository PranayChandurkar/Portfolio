# Personal Portfolio

**[🌍 Live Preview: pranaychandurkar-portfolio.vercel.app](https://pranaychandurkar-portfolio.vercel.app/)**

A modern, interactive, and fully responsive personal portfolio website built to showcase my projects, skills, and professional experience.

## 🚀 Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) (App Router)
- **Library:** [React](https://react.dev/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Icons:** [Lucide React](https://lucide.dev/) & [Remix Icon](https://remixicon.com/)
- **Email API:** [Resend](https://resend.com/)

## 🌟 Features

- **Hero Section:** A visually engaging introduction.
- **About Section:** Information regarding my background and core technical skills.
- **Projects Showcase:** Dedicated section displaying recent work, complete with dynamic data loaded from `src/data`.
- **Get in Touch / Contact:** Functional contact form integrated with Resend.
- **Smooth Animations:** Scroll and entrance animations powered by Framer Motion.
- **Responsive Design:** Optimized to look great on desktop, tablet, and mobile devices.

## 🛠️ Getting Started

First, clone the repository and install the necessary dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the portfolio in action.

## 📂 Project Structure

- `src/app` - Contains the Next.js App Router pages (e.g., `page.tsx`, `layout.tsx`) and API routes.
- `src/components` - Reusable UI components including `Navbar`, `HeroSection`, `AboutSection`, `ProjectSection`, and `GetInTouch`.
- `src/data` - JSON files (`project.json`, `extraProject.json`) managing the portfolio's content.
- `public` - Static assets such as images or favicons.

## 🤝 Contributing

Contributions, issues, and feature requests are always welcome! Feel free to check the issues page.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

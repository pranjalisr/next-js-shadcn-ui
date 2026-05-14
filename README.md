# ⚡ Next.js + shadcn/ui Starter Template

A fully configured **Next.js 15 + shadcn/ui** starter template with the complete shadcn/ui component library set up out of the box. Built with **React 19**, **TypeScript**, **Tailwind CSS**, and every Radix UI primitive you need — ready to build on immediately.

---

## 📁 Project Structure

```
next-js-shadcn-ui/
├── app/                  # Next.js App Router pages & layouts
│   └── globals.css       # Global CSS with Tailwind + CSS variables
├── components/
│   └── ui/               # shadcn/ui components (auto-generated)
├── hooks/                # Custom React hooks
├── lib/
│   └── utils.ts          # Utility helpers (cn, clsx, etc.)
├── public/               # Static assets
├── styles/               # Additional global styles
├── components.json       # shadcn/ui configuration
├── next.config.mjs       # Next.js configuration
├── tailwind.config.ts    # Tailwind CSS configuration
└── tsconfig.json         # TypeScript configuration
```

---

## 🛠️ Tech Stack

| Category        | Technology                            |
|-----------------|---------------------------------------|
| Framework       | Next.js 15.1.0 (App Router)           |
| Language        | TypeScript 5                          |
| UI Library      | React 19                              |
| Component Kit   | shadcn/ui — `default` style, neutral base |
| Styling         | Tailwind CSS 3 + CSS Variables        |
| Icons           | Lucide React                          |
| Theming         | next-themes (dark / light mode)       |
| Forms           | React Hook Form + Zod                 |
| Charts          | Recharts 2.15.0                       |
| Animations      | tailwindcss-animate                   |

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/pranjalisr/next-js-shadcn-ui.git
cd next-js-shadcn-ui

# Install dependencies
npm install
# or
pnpm install
```

### Running the Dev Server

```bash
npm run dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 Available Scripts

| Command          | Description                          |
|------------------|--------------------------------------|
| `npm run dev`    | Start the development server         |
| `npm run build`  | Build the app for production         |
| `npm run start`  | Start the production server          |
| `npm run lint`   | Run ESLint across the project        |

---

## 🧩 shadcn/ui Configuration

This project uses shadcn/ui with the following settings (`components.json`):

| Option           | Value                        |
|------------------|------------------------------|
| Style            | `default`                    |
| Base Color       | `neutral`                    |
| CSS Variables    | `true`                       |
| RSC Support      | `true`                       |
| TSX              | `true`                       |
| Icon Library     | `lucide`                     |
| Components alias | `@/components`               |
| UI alias         | `@/components/ui`            |
| Utils alias      | `@/lib/utils`                |
| Hooks alias      | `@/hooks`                    |

### Adding New Components

```bash
npx shadcn@latest add <component-name>
# e.g.
npx shadcn@latest add button
npx shadcn@latest add card
npx shadcn@latest add data-table
```

---

## 📦 Included shadcn/ui Components

This template ships with the **full shadcn/ui component set** pre-installed:

| Component          | Radix UI Primitive              |
|--------------------|---------------------------------|
| Accordion          | `@radix-ui/react-accordion`     |
| Alert Dialog       | `@radix-ui/react-alert-dialog`  |
| Aspect Ratio       | `@radix-ui/react-aspect-ratio`  |
| Avatar             | `@radix-ui/react-avatar`        |
| Checkbox           | `@radix-ui/react-checkbox`      |
| Collapsible        | `@radix-ui/react-collapsible`   |
| Context Menu       | `@radix-ui/react-context-menu`  |
| Dialog             | `@radix-ui/react-dialog`        |
| Dropdown Menu      | `@radix-ui/react-dropdown-menu` |
| Hover Card         | `@radix-ui/react-hover-card`    |
| Label              | `@radix-ui/react-label`         |
| Menubar            | `@radix-ui/react-menubar`       |
| Navigation Menu    | `@radix-ui/react-navigation-menu` |
| Popover            | `@radix-ui/react-popover`       |
| Progress           | `@radix-ui/react-progress`      |
| Radio Group        | `@radix-ui/react-radio-group`   |
| Scroll Area        | `@radix-ui/react-scroll-area`   |
| Select             | `@radix-ui/react-select`        |
| Separator          | `@radix-ui/react-separator`     |
| Slider             | `@radix-ui/react-slider`        |
| Switch             | `@radix-ui/react-switch`        |
| Tabs               | `@radix-ui/react-tabs`          |
| Toast              | `@radix-ui/react-toast`         |
| Toggle             | `@radix-ui/react-toggle`        |
| Toggle Group       | `@radix-ui/react-toggle-group`  |
| Tooltip            | `@radix-ui/react-tooltip`       |

### Additional UI Libraries

| Package                   | Purpose                          |
|---------------------------|----------------------------------|
| `cmdk`                    | Command palette (`⌘K`)          |
| `input-otp`               | OTP / PIN input fields           |
| `embla-carousel-react`    | Carousel / image slider          |
| `react-day-picker`        | Date picker calendar             |
| `react-resizable-panels`  | Resizable panel layouts          |
| `vaul`                    | Drawer / bottom sheet            |
| `sonner`                  | Toast notifications              |
| `recharts`                | Charts and data visualization    |
| `react-hook-form` + `zod` | Form handling and validation     |
| `date-fns`                | Date formatting utilities        |
| `next-themes`             | Dark / light theme switching     |

---

## 🚢 Deployment

Deploy instantly to [Vercel](https://vercel.com/):

```bash
npm run build
```


---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

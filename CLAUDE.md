## Project Overview

This is a Vite + React + TypeScript project with Tailwind CSS, shadcn/ui
components, Framer Motion, and various modern libraries set up as a single-page
application (SPA) using React Router.

## Project Structure

```
/
├── /node_modules/          # Project dependencies
├── /src/                  # Source code
│   ├── /components/       # UI components
│   │   └── /ui/           # shadcn/ui components
│   ├── /hooks/            # Custom React hooks
│   ├── /pages/            # Page components
│   ├── App.tsx            # Main application component
│   └── main.tsx           # Application entry point
│   └── index.css          # Global styles
├── package.json           # Project configuration and dependencies
├── tsconfig.json          # TypeScript configuration
├── vite.config.ts         # Vite configuration
```

## Key Features

### 1. Design System

Global styles are in `src/index.css`.

The project includes a comprehensive set of shadcn/ui components:

- **Forms**: Input, Textarea, Select, Checkbox, Radio Group, Switch, Slider,
  Button, Label, Form, Input OTP
- **Data Display**: Card, Table, Badge, Alert, Avatar, Calendar, Data Table
- **Feedback**: Toast, Sonner, Dialog, Alert Dialog, Tooltip, Hover Card, Drawer
- **Navigation**: Navigation Menu, Breadcrumb, Tabs, Dropdown Menu, Menubar,
  Pagination, Command, Context Menu, Sidebar
- **Layout**: Separator, Resizable, Scroll Area, Aspect Ratio, Collapsible,
  Sheet, Popover
- **Utilities**: Skeleton, Progress, Accordion, Toggle, Toggle Group
- **Data Visualization**: Chart, Carousel

### 2. State Management

- **React Query**: For server state management and data fetching
- **React Context**: For client-side state management

### 3. Routing

- **React Router DOM**: Hash-based routing for SPA navigation
- Initial routes:
  - `/` - Home page
  - `*` - Not found page (catch-all)

### 4. Additional Features

- **Date Handling**: date-fns for date manipulation
- **Forms**: React Hook Form with Zod validation
- **Icons**: Lucide React icons
- **Animations**: Tailwind CSS + Framer Motion animations
- **Theming**: Next Themes for dark/light mode support

## Setup and Installation

### Prerequisites

- Node.js
- bun (preferred for speed) or npm

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd <project-directory>

# Install dependencies
bun install
```

### Development

```bash
# Start development server
bun run dev
```

The development server will start at `http://localhost:3000` (or another
available port).

### Building for Production

```bash
# Build for production
bun run build
```

### Preview Production Build

```bash
bun run preview
```

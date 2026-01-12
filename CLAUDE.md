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
├── README.md              # Documentation
```

### Design System

Global styles are in `src/index.css`.

UI Components:

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

Additional Features:

- **Date Handling**: date-fns for date manipulation
- **Forms**: React Hook Form with Zod validation
- **Icons**: Lucide React icons
- **Animations**: Tailwind CSS + Framer Motion animations
- **Theming**: Next Themes for dark/light mode support

### State Management

- **React Query**: For server state management and data fetching
- **React Context**: For client-side state management

### Routing

- **React Router DOM**: Hash-based routing for SPA navigation
- Initial routes:
  - `/` - Home page
  - `*` - Not found page (catch-all)

# FigmaPoc
This Figma Make file includes components from [shadcn/ui](https://ui.shadcn.com/) used under [MIT license](https://github.com/shadcn-ui/ui/blob/main/LICENSE.md).

This Figma Make file includes photos from [Unsplash](https://unsplash.com) used under [license](https://unsplash.com/license).

# Figma PoC - Responsive Dashboard Application

A fully responsive dashboard web application built with React and Tailwind CSS, replicating a Figma design using a custom design system.

## ✨ Features

### 🎨 Design System Integration
- **Custom CSS Variables**: Complete design token system for colors, typography, spacing, and borders
- **29LT Bukra Font Family**: Professional Arabic/Latin typography with custom weights (400, 500, 700)
- **Dark Mode Support**: Built-in dark theme with all color variables
- **Responsive Design**: Mobile-first approach with desktop optimizations

### 📱 Responsive Layout
- **Desktop (≥768px)**: 2-column layout
  - Left Column: Accounts section, Credit Cards, Promotional cards (stacked vertically)
  - Right Column: Useful Links and Quick Pay (stacked vertically)
- **Mobile (<768px)**: Single-column layout
  - Collapsible sidebar with hamburger menu
  - Touch-optimized interactions

### 🎯 Dashboard Components
- **Accounts Overview**: Multi-currency account display with balances
- **Credit Cards**: Visual card representations with account details
- **Promotional Cards**: Marketing and feature highlights
- **Useful Links**: Quick navigation to common services
- **Quick Pay**: Streamlined payment interface
- **Navigation Sidebar**: Full menu with icons and labels

## 🎨 Design System

The application uses a comprehensive design system defined in `/styles/globals.css`.

### Color Palette

| Token | Light Mode | Usage |
|-------|------------|-------|
| `--primary` | `#FF5E00` | Primary actions, active states |
| `--accent` | `#FFF1E8` | Highlights, hover states |
| `--background` | `#FFFFFF` | Page background |
| `--foreground` | `#333333` | Primary text |

### Typography Scale

```css
--text-h1: 64px;    /* Major headings */
--text-h2: 32px;    /* Section headings */
--text-h3: 24px;    /* Subsection headings */
--text-h4: 20px;    /* Card titles */
--text-base: 14px;  /* Body text */
--text-label: 10px; /* Small labels */

# Components

This directory contains all React components organized by their purpose and scope.

## Structure

- `ui/` - Reusable UI components (buttons, inputs, modals, etc.)
- `page/` - Page-specific components
- `shared/` - Shared components used across multiple pages

## Guidelines

- **UI Components**: Keep them pure and reusable with proper TypeScript interfaces
- **Page Components**: Components specific to individual pages/routes
- **Shared Components**: Common components like headers, footers, navigation
- Use proper naming conventions (PascalCase for component files)
- Include TypeScript interfaces for all props
- Export components using named exports when possible

## Example Usage

```tsx
// UI Component
import { Button } from '@/components/ui/button';

// Page Component
import { HeroSection } from '@/components/page/hero-section';

// Shared Component
import { Header } from '@/components/shared/header';
```

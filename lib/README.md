# Lib

This directory contains utility functions, types, and helper modules for the application.

## Structure

- `utils.ts` - General utility functions and class utilities
- `helper/` - Helper functions and modules
- `types/` - TypeScript type definitions and interfaces

## Guidelines

- **Utils**: Pure functions for common operations (formatting, validation, etc.)
- **Helpers**: More complex utility modules and functions
- **Types**: Global TypeScript interfaces, types, and enums
- Keep functions pure and testable
- Use proper TypeScript typing
- Document complex functions with JSDoc comments

## Example Usage

```tsx
// Utility functions
import { cn, formatDate } from '@/lib/utils';

// Helper modules
import { apiHelper } from '@/lib/helper/api-helper';

// Types
import type { User, ApiResponse } from '@/lib/types';
```

## Common Patterns

- Use `cn()` for conditional CSS classes (tailwind-merge + clsx)
- Create custom hooks in `helper/` for reusable logic
- Define API response types in `types/`

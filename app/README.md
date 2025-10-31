# App Directory

This is the Next.js 13+ App Router directory containing pages, layouts, and route handlers.

## Structure

- `(front)/` - Route group for frontend pages
- `styles/` - Global styles and CSS files
- `not-found.tsx` - Custom 404 page
- `favicon.ico` - Website favicon

## App Router Features

- **File-based Routing**: Each folder represents a route segment
- **Layouts**: Shared UI components across routes (`layout.tsx`)
- **Loading States**: Loading UI components (`loading.tsx`)
- **Error Boundaries**: Error handling (`error.tsx`)
- **Route Groups**: Organize routes without affecting URL structure `(groupName)`

## File Conventions

- `page.tsx` - Page component (makes route publicly accessible)
- `layout.tsx` - Shared layout for route segment and children
- `loading.tsx` - Loading UI component
- `error.tsx` - Error UI component
- `not-found.tsx` - 404 page component

## Example Usage

```tsx
// page.tsx - Main page component
export default function HomePage() {
  return <div>Home Page</div>;
}

// layout.tsx - Shared layout
export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html>
      <body>{children}</body>
    </html>
  );
}
```

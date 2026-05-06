# Code Quality & Formatting Standards

To ensure consistency across Manero Premium Fullstack E-commerce Platform, please adhere to the following:

## 💻 Code Style
- **TypeScript**: Strict mode enabled. Explicitly define parameter and return types for all helper functions.
- **Formatting**: Strictly follow standard Prettier/ESLint rules.
- **Naming Conventions**:
  - Components & Types: PascalCase (`ProductCard`, `CartState`)
  - Hooks: camelCase starting with "use" (`useAuthState`)
  - Styles, Constants & Variables: camelCase or UPPER_SNAKE_CASE

## ⚡ React Native Best Practices
- Avoid inline function declarations in JSX wherever possible.
- Wrap complex computations inside `useMemo`.
- Prioritize native layout attributes and flexbox grid over absolute positioning.

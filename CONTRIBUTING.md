# Contributing to Manero Premium Fullstack E-commerce Platform

We maintain rigorous engineering and aesthetic standards in this repository. Please follow these guidelines:

## 📐 Architectural Standards
- **Component Design**: Keep components focused, atomic, and highly reusable. Avoid deep nesting.
- **Performance**: Never perform inline object/array declarations in render loops to avoid extra re-renders. Use `useMemo` and `useCallback` appropriately.
- **State Flow**: Maintain clear unidirectional data flow. Ensure asynchronous side effects are correctly encapsulated.

## ✨ Aesthetic Guidelines
- Always use the predefined design tokens (colors, font weights, spacing) rather than arbitrary inline styles.
- Include micro-interactions (subtle scale on hover/press) for all interactive components.

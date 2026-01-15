# AI Agent Instructions for Denuvo Slides Template

This file provides guidance for AI coding agents customizing this Vue.js presentation/slides template.

## Quick Start

1. **Slides**: Edit slide content in Vue components
2. **Styling**: Customize CSS/SCSS files
3. **Assets**: Add images to asset folders

---

## Files to MODIFY (Customize These)

### Slides Content
| Location | Purpose |
|----------|---------|
| `src/` | Slide components and content |

### Assets
| Location | Purpose |
|----------|---------|
| `public/` | Static assets |

---

## Vue Component Structure

```vue
<script setup>
// Component logic
</script>

<template>
  <!-- Slide content -->
</template>

<style scoped>
/* Slide styles */
</style>
```

---

## Build and Test

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

---

## Deployment Notes

**Build output**: `dist/` folder

Deploy the `dist/` folder to any static hosting service.

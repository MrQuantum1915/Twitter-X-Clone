# Twitter Frontend Clone

This repository contains the frontend implementation of a Twitter-like web application. The project is built using HTML and Tailwind CSS, with a focus on clean, modern UI and best practices for maintainability and scalability.

## Tech Stack Used
<img src="https://github.com/user-attachments/assets/237457a5-4d15-4b78-a411-907072f21c5b" alt="Image Description" width="100" height="100">

<img src="https://github.com/user-attachments/assets/12780a4b-0588-4a87-9f49-5e70aa00c1c4" alt="Image Description" width="200" height="100">

## Features
- Responsive layout with sticky navigation bar
- Sidebar, feed, and post area styled to mimic Twitter's look and feel
- Custom color theme (Twitter blue) via Tailwind configuration
- SVG icons and images managed in the `/assets` folder
- Reusable post container styles using Tailwind's `@apply` and custom classes
- Flexbox-based layouts for precise alignment
- All assets and styles optimized for frontend development

## Project Structure
```
assets/           # SVG icons and images
src/
  home.html       # Main UI (sidebar, feed, post area, etc.)
  input.css       # Tailwind custom CSS (with @apply, custom classes)
  output.css      # Compiled Tailwind output
  test.html       # Flexbox alignment demo
package.json      # Project dependencies and scripts
postcss.config.js # PostCSS configuration
 tailwind.config.js # Tailwind custom theme and content paths
```

## Getting Started
1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Build Tailwind CSS:**
    ```bash
    npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
    ```
    *or simply run:*
    ```bash
    npm run build
    ```
   ```
3. **Open `src/home.html` in your browser** to view the app.

## Notes
- This is a frontend-only project. There is no backend/API integration yet.
- All SVGs are optimized for use as `<img>` sources and reside in the `/assets` folder.
- Custom colors and reusable styles are defined in `tailwind.config.js` and `src/input.css`.

## Screenshot
*Website screenshot will be added here soon.*

---

Feel free to fork, modify, and use this project as a starting point for your own Twitter-like frontend!

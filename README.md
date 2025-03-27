# coffee-master-vanillaJS

This Single Page Application (SPA) is built entirely with **Vanilla JavaScript**, following a reactive programming pattern.
- Developed a Single Page Application (SPA) using Vanilla JavaScript, featuring a custom-built Router, State Management, Proxy, and Shadow DOM.
- Created modular Web Components to improve scalability and maintainability.
- Implemented dynamic cart functionality, enabling users to add items with instant badge updates reflecting quantities on the homepage without page refreshes.
- Provided intuitive cart management, allowing users to remove items or submit orders seamlessly through an integrated checkout form.

## Key Features

### 🚀 Reactive State Management
- State management is implemented using JavaScript `Proxy`, enabling automatic UI updates whenever state data changes.

### 🧩 Custom Web Components
- **Templates:** Defined within `index.html`.
- **Reusable Components:** Organized in the `Components` directory.
- **Encapsulation:** Components leverage the Shadow DOM for style isolation, modularity, and easy maintenance.

### 🔀 Custom JavaScript Router
- Lightweight client-side routing to dynamically load components without full-page reloads.
- Seamless navigation handled through the browser's History API (`pushState`, `popstate`).
- Supports dynamic routing with URL parameters (e.g., `/product-123`).
- Automatically scrolls to the top of the page upon navigation for enhanced user experience.

## Result
This setup provides a modular, maintainable, and performant frontend experience without external libraries or frameworks.

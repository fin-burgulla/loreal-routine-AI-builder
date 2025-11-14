## L'Oréal Routine Builder

Project overview

- Purpose: A lightweight, front-end focused personal project that demonstrates how to combine product data with conversational AI to generate personalized skincare/haircare routines and product recommendations.

- Audience: Built as a portfolio piece for recruiters and engineers to evaluate UX, client-side architecture, and integration patterns.

Key features:

- Product browsing: 
  Search and filter real L'Oréal product data presented in a responsive product grid.
- Product selection: 
  Select multiple products into a curated list to include in a routine.
- Routine generation: 
  Produce a step-by-step routine or product recommendations using an AI-driven generator.
- Conversational assistant: 
  Chat interface for follow-up questions and clarifications about routines and products.
- Accessibility and RTL support: 
  Includes an RTL toggle and accessible form controls.

Technology and implementation

- Languages: Vanilla HTML, CSS, and JavaScript for simplicity and portability.
- Styling: Custom CSS with responsive layout patterns and CSS variables for brand theming.
- Data: Local `products.json` serves as the product dataset used by the front-end.
- Integration: Demonstrates how to structure client-side requests and wire an AI routine generator (designed to be replaced with a real API key or server-side proxy in production).

Development notes

- The project intentionally avoids build tooling and frameworks to keep the codebase easy to review.
- `script.js` contains placeholder code for connecting to an AI routine generator; in a production setup, replace direct client-side API calls with a secure server-side proxy or environment-secured function.
- CSS variables are used for brand colors to make it straightforward to update theme tokens across the site.

License & contribution

- This repository is a personal project. Feel free to open issues or PRs if you'd like to collaborate or suggest improvements.

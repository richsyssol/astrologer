# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

Step 1.

1. Create a folder at any Location
2. Open folder in VS Code

Step 2.

1. Open terminal in VS Code
   npm create vite@latest
2. Project name:
3. Select React
4. Select Vite
5. Done. Now run:
   cd astrologer (Project name)
   npm install
   npm run dev
6. Show in terminal
   > astrologer@0.0.0 dev
   > vite

VITE v7.0.0 ready in 697 ms

➜ Local: http://localhost:5173/
➜ Network: use --host to expose
➜ press h + enter to show help

7. For Open link in mobile
   package.json - Update file
   "scripts": {
   "dev": "vite --host", //add this line
   "build": "vite build",
   "lint": "eslint .",
   "preview": "vite preview"
   },
8. Now run

Step 3. Tailwind setup
https://tailwindcss.com/docs/installation/using-vite
Install Tailwind CSS
Install tailwindcss and @tailwindcss/vite via npm.

1. npm install tailwindcss @tailwindcss/vite
2. Update file
   vite.config.js
   import { defineConfig } from "vite";
   import react from "@vitejs/plugin-react";
   import tailwindcss from "@tailwindcss/vite";

// https://vite.dev/config/
export default defineConfig({
plugins: [react(), tailwindcss()],
});

3.  Import Tailwind CSS
    Add an @import to your CSS file that imports Tailwind CSS.

        In File App.css

    @import "tailwindcss";
#   a s t r o l o g e r  
 #   a s t r o l o g e r  
 
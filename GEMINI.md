## Project Overview

This is a modern web platform for "AI Content Studio," a company specializing in creating innovative content using artificial intelligence. The project is built with Next.js 15, React 18, and TypeScript, and styled with Tailwind CSS. It features a modern design with a frosted glass effect, a video background, and a portfolio gallery. The application is structured using the Next.js App Router.

The project includes a custom `component-tagger-loader.js` and `VisualEditsMessenger.tsx`, suggesting a visual editing or content management integration.

## Building and Running

To get the project running locally, follow these steps:

1.  **Install dependencies:**
    ```bash
    npm install
    ```
    or
    ```bash
    bun install
    ```

2.  **Run the development server:**
    ```bash
    npm run dev
    ```
    or
    ```bash
    bun dev
    ```

3.  **Build for production:**
    ```bash
    npm run build
    ```

4.  **Start the production server:**
    ```bash
    npm run start
    ```

5.  **Lint the code:**
    ```bash
    npm run lint
    ```

## Development Conventions

*   **Styling:** The project uses Tailwind CSS for styling. Utility classes are preferred.
*   **Components:** The project is component-based. Reusable UI components are located in `src/components/ui`, while larger page components are in `src/components`.
*   **Structure:** The project follows the Next.js App Router structure, with pages and layouts defined in the `src/app` directory.
*   **Visual Editing:** The presence of `visual-edits` directory and related configurations in `next.config.ts` suggests a convention for integrating with a visual editing tool.

# Zhenverse's Personal Website

This repository contains the source code and content for my personal website and portfolio, hosted on GitHub Pages at [zhenverse.github.io](https://zhenverse.github.io).

## Tech Stack

*   **Framework**: [Astro](https://astro.build/) (Static Site Generation)
*   **Theme**: [Fuwari](https://github.com/saicaca/fuwari) (Tailwind CSS)
*   **Language**: TypeScript
*   **Package Manager**: pnpm
*   **Deployment**: GitHub Actions -> GitHub Pages

## Project Structure

To maintain a clear separation between website logic and personal content, this project is structured as follows:

*   `/src/content/`: Contains all Markdown/MDX files for blog posts, articles, and data collections.
*   `/src/components/` & `/src/layouts/`: Astro, UI framework components, and theme layouts.
*   `/public/`: Static assets such as personal photographs, original graphics, and custom branding assets.

## Local Development

Ensure you have Node.js installed. This project strictly requires **pnpm** for package management. Follow these steps to run the project locally:

1.  **Install pnpm (if not installed)**
    ```bash
    npm install -g pnpm
    ```

2.  **Clone the repository**
    ```bash
    git clone https://github.com/zhenverse/zhenverse.github.io.git
    cd zhenverse.github.io
    ```

3.  **Install dependencies**
    ```bash
    pnpm install
    ```

4.  **Start the development server**
    ```bash
    pnpm run dev
    ```
    The site will be available at `http://localhost:4321/`.

## License & Copyright

This project is **dual-licensed** to protect personal content while keeping the infrastructure open-source.

*   **Software & Source Code**: The core Astro framework, Fuwari theme components, and configuration files are released under the [MIT License](LICENSE).
*   **Personal Content**: All blog posts, articles, data collections within `/src/content/`, and static media within `/public/` are strictly **All Rights Reserved**. One may not reproduce, distribute, or modify my personal content without explicit written permission.

For more details, please refer to the `LICENSE` file.
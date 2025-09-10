# Netflix Clone

## Introduction

This is a Netflix Clone built with Next.js and Tailwind CSS. The application allows users to browse popular, top-rated, and upcoming movies. It demonstrates modern React and Next.js features, including server-side rendering, dynamic routing, and responsive design.

## Features

- Browse popular, top-rated, and upcoming movies.
- Search for movies by name.
- Responsive UI for desktop and mobile.
- Clean and modern design using Tailwind CSS.
- Modular component structure.

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm (comes with Node.js)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nguyenhuutam-vt/netflix-clone.git
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

4. **Open your browser and visit:**
   ```
   http://localhost:3000
   ```

### Project Structure

- `app/components/header.tsx`: Navigation bar and search.
- `app/page.tsx`: Main page.
- `app/toprated/page.tsx`, `app/upcoming/page.tsx`, `app/search/page.tsx`: Movie category pages.
- `public/`: Static assets.
- `globals.css`, `tailwind.config.ts`: Styling and Tailwind configuration.

## Documentation

- All main components are documented with comments in English.
- The project is structured for clarity and maintainability.
- You can easily add new features or pages by following the existing folder and component structure.

## Notes

- Fonts are loaded locally; make sure the `fonts` folder contains required font files or update font usage in `app/layout.tsx`.
- The application is for educational purposes and does not include all Netflix features.

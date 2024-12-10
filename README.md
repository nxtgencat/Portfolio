# Magic Portfolio

Magic Portfolio is a powerful, customizable portfolio website template built with [Once UI](https://once-ui.com) and [Next.js](https://nextjs.org), designed for designers and developers to showcase their work professionally and elegantly.

![Showcase](https://github.com/user-attachments/assets/9c8a0c6e-fdb3-4345-b45b-8d7226c126a2)


## Project Overview

Magic Portfolio offers a sleek, responsive portfolio solution with robust features:

### Key Features

- **UI Framework**: Leverages [Once UI](https://once-ui.com) for comprehensive design tokens, components, and theming
- **SEO Optimization**: 
  - Automatic open-graph and X image generation
  - Dynamic schema and metadata creation
- **Design Principles**:
  - Fully responsive across all device sizes
  - Minimalist design with timeless aesthetics
  - Extensive customization through data attributes
- **Content Flexibility**:
  - Conditional section rendering
  - Configurable page visibility for blog, work, gallery, and about/CV
  - Automatic social link generation
  - Optional URL password protection
- **Internationalization**: 
  - Full localization support using next-intl library

## Prerequisites

- Node.js v18.17+

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/once-ui-system/magic-portfolio.git
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run Development Server
```bash
npm run dev
```

### 4. Configuration

#### Edit Configuration
```
src/app/resources/config
```

#### Edit Content
```
src/app/resources/content (or content-i18n for localization)
```

### 5. Create Content

Add new blog posts or projects by creating .mdx files:
- Blog posts: `src/app/[locale]/blog/posts`
- Projects: `src/app/[locale]/work/projects`

## Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fnxtgencat%2Fportfolio&project-name=portfolio&repository-name=portfolio&redirect-url=https%3A%2F%2Fgithub.com%2Fnxtgencat%2Fportfolio&demo-title=Magic%20Portfolio&demo-description=Showcase%20your%20designers%20or%20developer%20portfolio&demo-url=https%3A%2F%2Fgithub.com%2Fnxtgencat%2Fportfolio&demo-image=https%3A%2F%2Fnxtgencat.vercel.app%2F_next%2Fimage%3Furl%3D%252Fimages%252Fprojects%252Fportfolio%252Fportfolio01.png%26w%3D1920%26q%3D75)

Easily deploy your Magic Portfolio to Vercel or other platforms supporting Next.js applications.

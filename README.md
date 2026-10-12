# SIPFUND Frontend

The frontend application for SIPFUND, built with Next.js, TypeScript, and Tailwind CSS.

## Tech Stack

- **Next.js** — React framework with App Router
- **TypeScript** — Type safety
- **Tailwind CSS** — Utility-first styling
- **shadcn/ui** — Customizable UI components
- **React Hook Form** — Form management
- **Zod** — Schema validation
- **Axios** — HTTP requests
- **Lucide React** — Icons

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

Clone the repository and navigate to the project directory:


Install dependencies:

```bash
npm install
```

### Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```text
src/
├── app/          # Pages, layouts, and routes
├── components/   # Reusable UI and layout components
├── features/     # Feature-specific modules
├── hooks/        # Custom React hooks
├── lib/          # Utilities and shared libraries
├── types/        # TypeScript types
└── config/       # Application configuration
```

## Development Workflow

- Create feature branches from `uat`.
- Submit pull requests to merge features into `uat`.
- Test changes in the UAT environment.
- Merge approved changes into `main` for production.

## Environment Variables

Store environment-specific configuration in `.env.local`. Never commit secrets, API keys, or credentials to Git.

## Build

To create a production build:

```bash
npm run build
```

To run the production build locally:

```bash
npm run start
```

## Deployment

## License

Proprietary — SIPFUND.

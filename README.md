# atWise

A modern web application built with Next.js, Sanity.io, and Chakra UI.

## Tech Stack

- **Framework**: Next.js 14
- **CMS**: Sanity.io
- **UI Library**: Chakra UI
- **Styling**: Emotion
- **Form Handling**: React Hook Form
- **Animation**: Framer Motion
- **Date Handling**: date-fns
- **Email**: EmailJS
- **TypeScript**: For type safety
- **MDX**: For content authoring

## Project Structure

```
├── app/                    # Next.js app directory
│   ├── (site)/            # Main website routes
│   ├── (studio)/          # Sanity Studio
│   ├── api/               # API routes
│   └── globals.css        # Global styles
├── sanity/                # Sanity.io configuration
├── public/                # Static assets
└── ...                    # Configuration files
```

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn
- Sanity.io account

### Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd atWise
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env` file in the root directory with the following variables:
```
NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=your_dataset
NEXT_PUBLIC_SANITY_API_VERSION=your_api_version
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Features

- Modern, responsive design with Chakra UI
- Content management with Sanity.io.
- Type-safe development with TypeScript
- MDX support for rich content authoring
- API routes for backend functionality
- Email integration with EmailJS


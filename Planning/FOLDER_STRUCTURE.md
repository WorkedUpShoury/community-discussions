fresher404/
│
├── frontend/                    # Frontend application (Next.js or React)
│   ├── public/                  # Static assets (images, favicon, etc.)
│   ├── pages/                   # Route-based files (if using Next.js)
│   ├── components/              # Reusable UI components (Navbar, Card, etc.)
│   ├── styles/                  # Global and utility styles (Tailwind config, CSS)
│   ├── data/                    # JSON/YAML/JS files for static resource data
│   ├── lib/                     # Utility functions (formatting, filtering, etc.)
│   ├── hooks/                   # Custom React hooks (optional)
│   └── app.config.js            # Global config, constants
│
├── backend/                     # Optional backend or CMS integrations
│   ├── api/                     # Backend routes or API handlers (Next.js, Express)
│   ├── scripts/                 # Scrapers, sync scripts, data processing
│   └── database/                # DB schema or static Airtable/Notion connections
│
├── docs/                        # Planning, strategy, and product documents
│   ├── MVP.md
│   ├── UVP.md
│   ├── ROADMAP.md
│   ├── USER_PERSONAS.md
│   ├── PROJECT_OVERVIEW.md
│   ├── SITEMAP.md
│   └── FEATURES.md
│
├── public/                      # Top-level static assets (optional)
│   └── robots.txt, manifest.json
│
├── .env                         # Environment variables (API keys, secrets)
├── .gitignore
├── README.md                    # Project introduction and setup guide
├── package.json
└── vercel.json / netlify.toml   # Hosting config (if deploying via Vercel/Netlify)

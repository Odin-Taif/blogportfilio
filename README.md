# - Next.js & Sanity CMS

## Quick Start

- Signup/Login to Sanity CMS (if not already)
- Create a Sanity Project
- Add required CORS & API settings in the project
- Create new Repository in Github
- Install Sanity Integration in Vercel
- Add required `.env` variables
- Deploy Sanity Studio - Content Manager
- Import Demo Content (as seen in live demo)
- Deploy to Vercel

To setup one click deployment, click the above link below and follow the steps.

## Local Development

1. ~root/`.env.local`

Change `.env.local.example` placed in the root folder and rename it to `.env.local` and add your sanity project ID. Get it from https://sanity.io/manage

```
NEXT_PUBLIC_SANITY_PROJECT_ID=xxyyzz
```

2. `/studio/.env.development` or `/studio/sanity.json`

To develop sanity cms locally, you also need to add the Project ID and Dataset in either `.env` or in `sanity.json` file.

```
# .env.development
SANITY_STUDIO_API_PROJECT_ID=xxyyzz
SANITY_STUDIO_API_DATASET=production

```

or you can directly replace the project ID in the `/studio/sanity.json`

### Run Next.js frontend

You can use the normal Next.js method to run the frontend. Just run the following command and a live server will open on `http://localhost:3000`

### Run Sanity Studio CMS
#   b l o g p o r t f i l i o  
 
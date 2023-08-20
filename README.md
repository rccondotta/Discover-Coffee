# Coffee Connoisseur
FrontEnd Application for discovering coffee shops!

## Getting Started
For this app to work, you need to configure the following environment variables in your .env.local file so please create a .env.local file in the root of your project right next to readme.md and the file needs to look like this:

```
NEXT_PUBLIC_FOURSQUARE_API_KEY=<value>
AIRTABLE_API_KEY=<value>
AIRTABLE_BASE_KEY=<value>
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=<value>
```

## Running the Project

1. In the terminal, run: `npm run dev`
2. Browse to the coffee store frontend at [localhost:3000](http://localhost:3000) and find coffee shops near you!

## Packages Used

* airtable - Airtable JavaScript library
* classnames - A simple JavaScript utility for conditionally joining classNames together
* swr - React Hooks library for data fetching
* unsplash - https://unsplash.it/ JavaScript generator

## Concepts

* Routing with Next.js
* Styling in Next.js
* Hydration, SEO, and Different Rendering Techniques
* Statics and Dynamic Pages
* Coffee Stores by Location
* Serverless Functions
* Data Storage using Airtable
* SWR with Client Side Rendering
* Deployment and Build Optimization

# throne-of-glass-api

- Build 2 APIs that will return Throne Of Glass Characters :

  - GET /api/characters/
  - GET /api/characters/:id

- Node/Express API with TypeScript
- MySQL on PlanetScale
- Web Scraping with Cheerio
- Scrape Characters from https://throneofglass.fandom.com/wiki

Prerequisite:
Create an acoount in PlanetScale: https://planetscale.com/
Create databse using CLI below :
pscale database create tog

Seed data to database:
pscale connect tog dev --execute 'npm run seed:db'

Start :
pscale connect tog dev --execute 'npm run dev'
//this willl load the database from pscale without needing to specify the environment variable, cool right ? 😎

Build and start:
pscale connect tog dev --execute 'npm run start'

# County Intelligence Platform — Knowledge Graph Explorer

An interactive explainer for the County Intelligence Platform: how LightRAG + AI turns 3,232 county documents into an answerable knowledge graph for disaster response planning.

## What this is

A single-file static web app (`index.html`) that demonstrates:

- **Live knowledge graph visualization** — interactive canvas showing counties, hazards, risk indices, and their relationships
- **Architecture explainer** — how documents → graph → AI query layer works
- **Query examples** — representative answers the platform produces
- **Use cases** — disaster response applications

## Live platforms

- **This explainer**: [kg.jbf.com](https://kg.jbf.com)
- **Live LightRAG instance**: [explorer.jbf.com](https://explorer.jbf.com)

## Data sources

- FEMA National Risk Index (18 hazard types per county)
- CDC Social Vulnerability Index 2022
- CDC PLACES 2023 (health outcomes)
- Census ACS 2022
- FEMA Major Disaster Declarations

## Tech stack

- Static HTML/CSS/JS — zero dependencies, zero build step
- Canvas-based graph visualization
- Deployed on Vercel

## Deploy

```bash
# Clone
git clone https://github.com/franzenjb/kg-explainer.git
cd kg-explainer

# Deploy to Vercel
vercel --prod
```

## Disclaimer

Independent research project. Not an official American Red Cross application.
Built by Jeff Franzen · [jbf.com](https://jbf.com)

# Roman Magdalenko

Founding Deployment Strategist. I build pilot-to-production systems for enterprise AI companies, with a focus on Conversation Intelligence, Revenue Intelligence and agentic AI. The stretch between a successful pilot and a repeatable, profitable deployment is where most companies stall.

26 years in enterprise sales: VP Sales EMEA at ABBYY LS, CCO at RedLab, now founder and CEO at SalesAI. 54 enterprise deployments, and in the last three years 200+ AI pilots launched or rescued.

Based in Valencia, Spain. Open to roles here or remote.

Most of my production code lives in private repos. What I can open, I put here.

## Now building

**SalesAI** - Conversation Intelligence and Revenue Intelligence platform for enterprise sales teams. The approach we sell is Managed Revenue Growth: a proprietary LLM sits on a sales knowledge graph of 70+ entity nodes, pulls 19 entities out of every customer conversation, writes them back into the CRM, and turns that into a forecast, a risk list and a coaching plan for each rep.

The platform combines speech analytics, CRM automation, deal intelligence, pipeline risk assessment and AI sales coaching.

Speech analytics answers how the call went. The graph answers where the money is.

**[Tour de Castles](https://tourdecastles.com)** - a model-agnostic travel intelligence platform for discovering the hidden gems of Spain and Portugal. We are building the knowledge and tool layer that turns a general-purpose AI assistant into an Iberian travel specialist, without training our own LLM.

The platform combines a grounded destination knowledge graph, around 900 castle guides, curated GPX routes, Wikidata and transport data. Its planning engine is designed to build feasible itineraries around cultural heritage, nature and local experiences, taking travel time, opening hours, transport constraints and source provenance into account.

The architecture is bring-your-own-model (BYOM): travelers connect their preferred AI assistant through Model Context Protocol (MCP), while hotels, tour operators and destination organizations can integrate planning capabilities through APIs or branded widgets. The model handles inference; TdC provides domain knowledge, routing tools and grounding.

**[Tour de Castles MCP Server](https://app.tourdecastles.com/mcp/me/)** - an OAuth-protected remote MCP endpoint designed to give AI assistants direct access to our destination knowledge graph, travel data and itinerary planning tools. Rather than building another standalone AI chatbot, we are building domain-specific infrastructure that compatible AI agents can use to discover destinations, retrieve grounded information and construct feasible travel plans. Consumer connector rollout and itinerary quality validation are in progress.

The business goal is to help partners convert existing travel intent into longer stays, booking referrals and visits beyond crowded hotspots. The long-term metric is **incremental visitor spending redirected to underserved territories**, not pageviews.

**[smartsales.ai](https://smartsales.ai)** - my English writing on revenue architecture, and the EN/ES content engine that ships it.

## What I actually do

- Knowledge graphs over messy human data: entity extraction, ontology design, grounding gates, health metrics you can put in CI.
- Revenue systems: CRM as an event pipeline (firehose into D1), anonymous-to-contact stitching, an AI SDR that runs outbound without a human in the loop.
- Claude Code as an operating system: skills, memory architecture, crons. One founder running sales, marketing and product on it.
- Sales methodology as code. MEDDIC, SPICED and BANT are not slides for me, they are schemas.
- Enterprise AI deployment: customer discovery, use-case qualification, pilot design, production rollout, adoption and measurable ROI.
- Conversation and revenue intelligence: speech analytics, conversation-to-CRM automation, deal scoring, forecasting and AI sales coaching.
- AI agent systems: agent orchestration, MCP integrations, knowledge grounding, workflow automation and GTM engineering.

## How the three repositories fit together

They are not a portfolio. They are one argument in three parts: what is true
([the knowledge graph](https://github.com/romanmagdalenko/castle-graph-engine)),
what happened ([the behaviour layer](https://github.com/romanmagdalenko/crm-on-cloudflare)),
and how one person executes against both ([the skills](https://github.com/romanmagdalenko/claude-gtm-skills)).

All three were built before there was a business model to justify them, which is
the point. The reasoning: [Designing for Optionality](https://smartsales.ai/en/writing/designing-for-optionality/).

## Writing

- [smartsales.ai](https://smartsales.ai) - Revenue Architecture, in English.
- [LinkedIn](https://linkedin.com/in/romanmagdalenko) - shorter notes from the room, not from the deck.

## Stack

TypeScript, React, Node. Cloudflare Workers, D1, KV, R2. Python. Postgres. Claude API and MCP servers. Wikidata and SPARQL. GitLab CI, Kubernetes, Supabase.

## Reach me

[LinkedIn](https://linkedin.com/in/romanmagdalenko) · [smartsales.ai](https://smartsales.ai) · [Book 30 minutes](https://cal.com/roman-smartsales/30min)

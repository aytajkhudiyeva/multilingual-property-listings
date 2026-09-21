# Multilingual Property Listings

Independent Dubai real estate listing demo. Enter verified property facts and generate English, Arabic and Russian drafts. With `OPENAI_API_KEY`, a server-side OpenAI call writes the descriptions. Without a key, transparent templates keep the demo runnable.

Node 20+: `npm start`, then open `http://127.0.0.1:4202`. Run `npm test`. Set `.env.example` values in the server environment; `.env` is not loaded automatically.

An agent must verify facts, translations and advertising permissions before publishing. [Dubai Land Department ad permit guidance](https://dubailand.gov.ae/en/eservices/real-estate-ad-permit/).

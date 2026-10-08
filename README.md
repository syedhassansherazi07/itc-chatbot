# ITC - Immunity Therapy Center | Grounded Chatbot

> A healthcare chatbot that never guesses. If it's not in the source, it doesn't answer.

  Live: https://shahjee-25.app.n8n.cloud/assistant/166e467d-9c11-4589-851d-dcc551a92ec9
  Repo: https://github.com/syedhassansherazi07/itc-chatbot

### What it does
- Scrapes 7 official PlacidWay pages weekly
- Answers ONLY from that data with source links
- Says "I don't have this information..." if not found - zero hallucination

### Flow
Timer -> Scrape 7 Pages -> Merge -> AI Agent -> Chat with Citations

### Testing - 100% Pass
- Cost? -> $18,995 / $30,000 + source
- Booking / Weather? -> Correctly refuses
- Hi -> Friendly greeting

### File
`ITC Immunity Therapy Center - Grounded Knowledge Chatbot.json` - Import in n8n and it's live.

Built by Syed Hassan Sherazi - For PlacidWay

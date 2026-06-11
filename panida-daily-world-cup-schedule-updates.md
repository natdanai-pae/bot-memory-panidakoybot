---
type: bot-memory
memory_type: detailed-topic
bot: panidakoybot
created: 2026-06-11
updated: 2026-06-11
tags:
  - bot-memory
  - panidakoybot
  - cron
  - football
  - world-cup
---

# Daily World Cup Schedule And Results Updates

User asked for daily updates and reports on the FIFA World Cup match schedule, daily results, and highlight links.

## Schedule

- Daily at 08:10 Thailand time.
- Hermes cron job ID: `9a28186c0406`.
- Delivery: origin Telegram chat with Choncharoen Sawangrat.

## Content

- Focus on FIFA World Cup 2026 men's tournament unless the user later specifies another tournament.
- Use current sources each run, starting with FIFA official fixtures/schedule.
- Convert match times to Thailand time (ICT, UTC+7).
- Include today's matches, latest results for each matchday when relevant, next upcoming matches, watch points, and source links.
- Include official/licensed highlight links for completed matches when available.
- Prioritize FIFA official match pages/highlights, FIFA+, FIFA official YouTube, official broadcaster channels, or licensed sports news sources.
- Do not include suspicious re-upload or piracy links. If official highlights are not available yet, say so clearly instead of guessing.

## Tone

- Thai concise secretary tone.
- Address the user as “นาย”.
- End politely with “ค่ะ” where appropriate.

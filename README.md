# AALC — Ascension & Absolute Life Command

A functional, mobile-first local prototype implementing the core AALC philosophy.

## Included
- Cinematic first launch with rotating discipline/mastery quotes
- Username + AALC ID + local prototype password gate
- Multi-step personalized initialization with skip controls
- Custom master goal and unlimited custom skills
- Optional Mental, Knowledge, Skills, Spirituality and Physical domains
- Independent E→X domain ranks, XP, levels and progression paths
- Goal-oriented martial-arts selection
- Theme switching
- Dashboard personalization
- White Room unlock gate
- Reading Lab
- Structured simulated KAROS (explicitly not a real AI)
- Local persistence using browser localStorage
- No fake global rankings, cloud sync, chat, or real-time AI

## Run
Open `index.html` in a modern browser. For best results, serve the folder from a local static server.

## Production next steps
1. Replace localStorage authentication with a secure backend using password hashing.
2. Add a database and API for users, profiles, progression records, connections and messages.
3. Move rank/XP calculations into a shared server-side progression service.
4. Add authenticated server-side AI access for KAROS; never expose provider API keys.
5. Add real cloud leaderboards with verified records only.
6. Add tests for progression, personalization, authorization and safety boundaries.

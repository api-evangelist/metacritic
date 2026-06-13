# Metacritic

Metacritic is a review aggregator that collects critic and user scores for games, movies, TV shows, and music, computing a weighted Metascore for each title.

The Metacritic API (provided via Fabric Origin / IVA / Gracenote) gives programmatic access to Metascores, user scores, individual critic reviews, publication details, and entertainment rankings for movies and television. Access requires a paid Fabric Origin subscription with per-account approval.

**API Base URL:** `https://api.origin.fabricdata.com/api/Metacritic`

**Authentication:** `Ocp-Apim-Subscription-Key` header or `subscription-Key` query parameter

**Endpoints:**
- `GET /Movie/{Id}` — Metacritic data for a movie
- `GET /TV/{Id}` — Metacritic data for a TV show (optional `SeasonNumber` param)

**Developer Portal:** https://developer.origin.fabricdata.com/

**Website:** https://www.metacritic.com/

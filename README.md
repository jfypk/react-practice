# Project: "Weather Dashboard Lite"
## Summary
Build a small React + TypeScript app that fetches and displays the current weather for a user-input city using a free weather API (e.g., OpenWeatherMap).

## Requirements
1. Input & Fetch
- A text input for city name (e.g., "New York")
- A "Get Weather" button
- On submit, fetch current weather data from an API
2. Display
- Show:
  - City name
  - Current temperature
  - Weather description
  - Icon (optional)
- Handle loading and error states cleanly
3. TypeScript
- All data and props should be properly typed
- Use interfaces for weather response and component props
4. UX
- Show a loading indicator while fetching
- Show user-friendly error message if city is not found or API fails
5. Stretch (Optional)
- Temperature toggle: °C ⇄ °F
- Cache the last 3 searched cities (in memory or localStorage)
- Basic responsive layout

## What It Tests
- TypeScript: Custom types, response typing, strict mode discipline
- React	Hooks: (useState, useEffect), conditional rendering
- API integration:	Async/await, error handling, data modeling
- Component design:	Separation of concerns, reusable UI elements
- UX quality:	Loading/error states, polish under time pressure

# Deliverables
Code in GitHub or CodeSandbox
README with setup instructions + notes if they didn’t finish

# Optional Starter API
Use the [OpenWeatherMap Current Weather](Optional Starter API
Use the OpenWeatherMap Current Weather API — returns JSON like:

json
Copy
Edit
{
  "name": "New York",
  "main": { "temp": 297.15 },
  "weather": [{ "description": "clear sky", "icon": "01d" }]
}
Free tier works without credit card and has fast signup.) API — returns JSON like:

```json
{
  "name": "New York",
  "main": { "temp": 297.15 },
  "weather": [{ "description": "clear sky", "icon": "01d" }]
}
```
Free tier works without credit card and has fast signup.


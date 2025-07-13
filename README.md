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
- All API responses and props should be strictly typed — no any
- Prefer interface or type with discriminated unions where relevant
- Use strict mode if using your own setup
- API responses must be typed
4. UX
- Show a loading indicator while fetching
- Show user-friendly error message if city is not found or API fails
5. Senior-Level Instructions
In addition to the core, we expect the following from senior candidates:
- Architecture & State
  - Use useReducer to manage async state transitions (idle/loading/success/error)
  - Organize code with logical separation of concerns (e.g., components/, types/, hooks/)
  - If time allows, abstract weather logic into a custom hook (useWeatherSearch)
  - Keep components clean and focused — avoid deeply nested state
- Extensibility
  - Add a search history feature (last 3 searched cities) via either:
  - Local state with useReducer OR
  - A Context-based provider (bonus for clean usage)
  - Clicking a previous city should re-fetch its weather
- Testing (Optional but Encouraged)
  - Add 1–2 unit or integration tests using Jest and React Testing Library
  - Example: test that weather fetches and displays correctly, or handles an API error
- Temperature toggle: °C ⇄ °F
- Cache the last 3 searched cities (in memory or localStorage)
- Basic responsive layout
- Basic error boundary or fallback UI

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
Use the [OpenWeatherMap Current Weather](https://openweathermap.org/current) API — returns JSON like:

```json
{
  "name": "New York",
  "main": { "temp": 297.15 },
  "weather": [{ "description": "clear sky", "icon": "01d" }]
}
```
Free tier works without credit card and has fast signup.


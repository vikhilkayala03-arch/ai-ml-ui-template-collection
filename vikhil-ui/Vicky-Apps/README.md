# Vicky Apps – four apps, plain HTML/CSS/JS (no build step)
Open `index.html` (or any app's `index.html`) in a browser. Data you enter is saved in your browser only.

## Vicky Academy – food & culture (cream + orange; the original app)
- Learn food etiquette with lessons and quizzes, earn XP, streaks and badges.
- AI Menu Scanner (type dish names), Chef Vicky chat, 6 countries, adventures, recipes, profile.
- Click any cooking-skill card to open a full lesson. Edit content in `vicky-academy/js/data.js`.

## GreenRoots – agriculture (sidebar layout, forest green + marigold)
- Crop Advisor: ranks crops by season, soil and water; shows estimated profit per acre.
- Plant Doctor: tick symptoms, get likely causes and organic-first fixes.
- Profit Calculator: cost, revenue, ROI, break-even price, and a "price falls 20%" test.
- Sowing Calendar: 15 crops across 12 months with the current month highlighted.
- Field Weather: live Open-Meteo forecast (no API key) with spraying/irrigation advice.
- Voice assistant: speak a question (Chrome) and hear the answer.
- Edit crops, costs and prices in `js/data.js`. Values are illustrative.

## StudyNest – school & college (notebook/graph-paper theme)
- Smart Planner: day-by-day plan weighted by exam date and difficulty.
- Focus Room: Pomodoro timer with brown-noise and rain sounds generated in the browser.
- Flashcards: spaced repetition (1, 3, 7 day boxes).
- Notes → Quiz: paste notes, get a fill-in-the-blank quiz.
- Grades: CGPA calculator and "how many classes can I skip" attendance planner.
- Today dashboard: next exam countdown, focus minutes, streak, cards due.

## Wanderly – travel (dusk gradient, floating nav)
- Trip Planner: itinerary + budget breakdown as a boarding pass for 6 destinations.
- Split Costs: shared expenses with the fewest payments to settle up.
- Smart Packing: checklist by climate, length and activities, with saved ticks.
- Phrasebook: 8 phrases x 4 languages, spoken with the device's voices.
- Currency: live rates (open.er-api.com) with stored fallback rates.
- Add destinations in `js/data.js`.

## Notes
- Fonts load from Google Fonts; without internet the apps fall back to system fonts.
- "AI" here is built-in rules and heuristics that work offline. To connect a real AI model, add a small backend and call it from the assistant/planner code. Never put API keys in front-end code.
- GreenRoots advice and the Plant Doctor are general guidance. Confirm with your local agriculture officer.


## 2026 UI collection redesign
The main `index.html` is now a responsive template-gallery homepage inspired by modern template libraries and UI galleries. It includes search, category filters, sorting, quick previews, responsive cards, and direct links to all four apps. The original homepage is preserved as `index-original.html`.


## Ramsai Sector Apps
The `ramsai-apps/` folder contains the integrated Ramsai collection: MelodyWave, NovaBank, PulseTrade and ForgeFlow. Open them from the main `index.html` dashboard under **Ramsai Apps**.

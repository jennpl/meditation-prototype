Weather-driven meditation app that intercepts the habit of checking 
the weather and redirects it into a mindfulness moment

## Idea

Most meditation apps ask you to build a new habit from scratch while ignoring competing attention demands on your phone. 
openAIR uses an existing one: checking the weather. The goal is to turn this habit into a moment of mindfulness, eventually to make the app unnecessary.

## How it works

- Detects local weather via Open-Meteo API
- Selects a meditation practice based on current conditions
- No accounts, no notifications, no engagement mechanics

## Product philosophy

- **Behavioral interception** over habit creation
- **Environmental cues** over device dependency  
- **Obsolescence** as the north star — success means you no longer need the app

## Built with

- HTML, CSS, JavaScript
- Open-Meteo API (weather data)
- Vercel (deployment)

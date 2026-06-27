# Travel Advisor

A React travel discovery app using map components, place cards, location based browsing, and Material UI.

## Product story

Travel Advisor fits Gokhan's hospitality profile because it is about helping people choose where to go, what to eat, and how to explore an area. The app demonstrates API connected frontend work with a practical consumer workflow.

## What it demonstrates

| Area | Evidence |
| --- | --- |
| API connected UI | Place data and map data drive the interface. |
| Component design | Header, list, map, and place detail components separate responsibilities. |
| Material UI | The project uses MUI components and styling patterns. |
| Location based UX | Users can browse places through geography and filters. |

## Stack

React, JavaScript, Material UI, Axios, Google Maps tooling, Create React App.

## Run locally

```bash
npm install
npm start
```

Build for production.

```bash
npm run build
```

## Project structure

```text
src
├── components
│   ├── Header
│   ├── List
│   ├── Map
│   └── PlaceDetails
├── App.js
└── index.js
```

## Next improvements

1. Move API keys into environment variables and document setup.
2. Add screenshots of the map and place list flow.
3. Add loading and error states for external API calls.
4. Add filters for restaurants, hotels, and attractions.
5. Add deployment instructions.

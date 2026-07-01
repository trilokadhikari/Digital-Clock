# Digital Clock

A small React app that displays a live digital clock with hours, minutes, seconds, and AM/PM formatting.

## Features

- Real-time clock updates every second
- 12-hour format with leading zeros
- Simple React component structure using `useState` and `useEffect`
- Built with Vite for fast development


## Project Structure

- `src/App.jsx` — application entry component
- `src/DigitalClock.jsx` — digital clock component with timer logic
- `src/index.css` — styles for the clock
- `package.json` — project dependencies and scripts

## Notes

- The clock updates every second using `setInterval` inside a React effect.
- The interval is cleaned up when the component unmounts.


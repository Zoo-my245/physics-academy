# Physics Academy — Unit 1 Prototype

A reusable React/Vite lesson engine, with Lesson 1.1 populated and Lessons 1.2–1.5 outlined.

## Run locally

1. Install Node.js 18+.
2. In this folder run `npm install`.
3. Run `npm run dev` and open the address printed by Vite.
4. Run `npm run build` to create a production-ready `dist` folder.

## Reusable architecture

- `src/content.js` — Unit, topic, lesson, section, question and activity data.
- `src/main.jsx` — Reusable rendering components and local progress tracking.
- `src/style.css` — Responsive styling and accessibility settings.

## Add a lesson

Replace a planned lesson entry in `src/content.js` with an object containing `id`, `title`, `objectives`, `sections`, and `questions`. Each section may contain `title`, `paragraphs`, `example`, and `activity`. Supported activity types: `choice`, `classify`, `explorer`.

## Prototype limitations

Progress is stored only in the browser's localStorage. There is no login, cloud sync, backend, or server-side persistence. This prototype does not yet include full simulations, adaptive learning, achievements, or complete screen-reader testing. It does include keyboard-accessible native controls, text sizing, contrast toggle, responsive layout, and a functional mastery check.

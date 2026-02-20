# Contributing

Thanks for contributing to `opinion-diffusion-sim`.

## Development Setup

1. Install Node.js 20+.
2. Install dependencies:
   - `npm install`
3. Run local development server:
   - `npm run dev`
4. Open:
   - `http://localhost:4000/sim`

## Project Structure

- `src/sim/`: parsers, language utilities, simulation engine, types
- `src/routes/`: API and UI route handlers
- `web/`: browser interface (landing page, simulator page, styling, scripts)
- `docs/`: user documentation and PDFs
- `test/`: parser, engine, and tutorial-example tests

## Before Submitting a Pull Request

Run these commands and ensure they pass:

1. `npm run check`
2. `npm run build`
3. `npm run test`

## Pull Request Guidelines

1. Keep changes focused and explain intent clearly.
2. If behavior changes, add or update tests.
3. If user-facing workflows change, update docs in `docs/`.
4. Include a concise summary:
   - what changed
   - why it changed
   - how it was tested

## Issue Reporting

When opening issues, please include:

- expected behavior
- actual behavior
- steps to reproduce
- relevant NGL/ORL snippets when applicable
- screenshots or logs if available

## Scope and Direction

This project centers on:

- network specification (Network Generation Language)
- opinion dynamics specification (Opinion Rule Language)
- interactive visualization of evolution over time

Contributions aligned with these goals are especially helpful.

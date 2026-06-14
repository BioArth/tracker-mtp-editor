# Polyend Tracker Pattern Editor

A web-based editor for creating and editing patterns for the **Polyend Tracker** hardware. Powered by [`tracker-lib`](http://github.com/polyend/tracker-lib) along with other frameworks.

**Live Demo:** https://polyend.sandroid.xyz/patterned/

For a quick overview, check out this video:
[link to youtube video]

----

## Features

* **Pattern Editor**: Edit notes, instrument assignments, and FX parameters in a classic tracker-style grid.
* **Pattern File Support**: Uses `tracker-lib` to read/write Polyend Tracker pattern files.
* **Full Keyboard Control**: I mean... you don't really want to use the mouse, do you? :stuck_out_tongue:

----

## Technical Stack

* [`tracker-lib`](http://github.com/polyend/tracker-lib) (handles read/write of `.mtp` files)
* **Framework**: [Vue 3](https://vuejs.org/) (Composition API, `<script setup>`)

----

## Getting Started

### Installation

1. Install all dependencies:
   ```bash
   npm install
   ```

2. Run the development server locally:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to the local server URL (typically `http://localhost:5173`).


### Scripts

* `npm run dev`: Starts the local development server.
* `npm run build`: Compiles and bundles the application for production.
* `npm run test`: Runs formatting checks, ESLint, and type checks.
* `npm run lint`: Runs ESLint on source files.
* `npm run typecheck`: Validates TypeScript without compiling.

----

## Future plans

There are no immediate future plans for this example. If anyone wants to continue development, I will happily accept PRs or add you as a contributor to this repository.

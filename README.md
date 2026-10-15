# aap-example-sveltekit

A minimal **SvelteKit (server-rendered, Node adapter)** app, kept as a deploy example for [AI Admin Panel](https://aiadminpanel.com).

AI Admin Panel deploys it from this repository with **Git Deploy** (and **AI Deploy**) and checks
the result regularly: the page at `/` must contain the marker `aap-example:sveltekit`. Use it to see how
your own SvelteKit (server-rendered, Node adapter) project is built, or as a starting point.

Uses `@sveltejs/adapter-node`, SvelteKit's documented adapter for your own server. `npm run build` writes `build/`, and `npm start` runs it and honours `$PORT`.

- The app listens on `$PORT` (default 8080).
- No secrets in this repository.
- License: MIT.

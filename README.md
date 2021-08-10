# Sentry Hackweek Notifications

This project uses [Astro](https://astro.build).

### Get Started 

| Command         | Action                                      |
|:----------------|:--------------------------------------------|
| `npm install`   | Installs dependencies                       |
| `npm start`     | Starts local dev server at `localhost:3000` |
| `npm run build` | Build your production site to `./dist/`     |


### Structure
 
```
/
├── public/
│   ├── robots.txt
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── Tour.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

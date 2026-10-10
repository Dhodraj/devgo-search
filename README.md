# devgo-search

A search page built on Google's Programmable Search API. Type a query and results come back without a page reload.

Built in 2021. Live at [devgo-f4d7c.web.app](https://devgo-f4d7c.web.app/).

A React app. A custom hook, `useGoogleSearch`, calls the Custom Search JSON API and a Context holds the current term. The UI uses Material UI.

## Run it

```bash
npm install
npm start
```

The API key and search-engine ID live in `src/keys.js`, which ships with placeholders. Put your own Programmable Search Engine key and ID there first. Get them from the [Programmable Search Engine](https://programmablesearchengine.google.com/) control panel.

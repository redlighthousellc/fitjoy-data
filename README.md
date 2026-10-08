# fitjoy-data

Public data for the Fitjoy app, served by GitHub Pages at https://exercises.fitjoy.us/.

- `exercises.json`: the Add Exercise suggestion list the app checks once a day.

**Don't edit files here by hand.** The source of truth is `src/config/exerciseLibrary.json` in the
app repo. Change it there, bump `version`, and run `npm run publish:exercises`, which validates the
list and pushes it here.

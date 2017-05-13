# wf_webcontent

This is an experimental pebble app of a watch face diplaying web sourced content via an API (visit `https://openweathermap.org/` to generate yours).

A `config.js` file must be added to the folder `./src/pkjs/` in order to provide the API key required to source data to the application. It must define and expose a function of signature `getConfig(configName)` which will respond with the API key as a string when called with the parameter value `OPENWEATHERMAP_API_KEY`.

**Have fun!**

This repo shows using environment variables in `index.html`.

There is a `apps/demo/.env` file that contains `NX_FOO` variable used in `index.html`.

Run the server (`nx serve demo`), and in the page you should see `NX_FOO: bar`, as well a `console.log` of the `process.env.NODE_ENV` value.

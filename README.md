# Badrap App API

This repository contains the OpenAPI 3.0 specification for the Badrap App API, as well as tooling for auto-generating documentation from the specification.

Whenever the `main` branch gets updated a new version of the documentation is generated and uploaded to GitHub Pages at https://badrap.github.io/apidoc.

## Development

Start the development environment with the following command:

```sh
docker-compose up --build
```

When the containers are running the current version of the documentation is served at http://localhost:8081.

The documentation is regenerated whenever the OpenAPI specification file is saved (with a small delay). Note that the browser will not automatically refresh when the page changes - you have to do it manually.

# Replit setup

This project is a static HTML page with its styles embedded in `index.html`.
It has no package dependencies, backend, or required environment variables.

## Run

The configured `Start application` workflow serves the project on port 5000:

```sh
python3 -m http.server 5000 --bind 0.0.0.0
```

The Python 3.11 runtime is used only as a lightweight static file server.
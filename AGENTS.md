# Project Instructions

## Local Jekyll workflow

Use the project Docker container for all local Jekyll build, test, and review work. Do not rely on the host Ruby or Bundler installation; the repository pins dependencies that may not be available on the host.

- Build the site with:

  ```sh
  docker compose run --rm jekyll bundle exec jekyll build
  ```

- Run the local review server with:

  ```sh
  docker compose up jekyll
  ```

  Then review the site at `http://localhost:4000`.

- Run one-off Jekyll checks through the same service, for example:

  ```sh
  docker compose run --rm jekyll bundle exec jekyll doctor
  ```

The Compose service bind-mounts the repository at `/site` and stores the bundle in the named `bundle` volume, so source edits are reflected in the container immediately.

GitHub Pages is configured to use GitHub's managed legacy Jekyll build from the `main` branch and repository root. Keep local Docker dependencies aligned with the committed `Gemfile.lock`; do not add a separate deployment workflow unless the repository's Pages publishing mode changes.

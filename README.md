# async-tokio-template

A [cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a deamon (e.g. webserver) written in Rust with tokio. It includes handy features like a `Dockerfile` for a really slim docker image, a simple github actions workflow to build and push the image to the github package registry and a command to reload any `GlobalState` (see `src/global_state.rs`) like config files without restarting the server.

## Usage
Just run `cookiecutter https://github.com/LevitatingOrange/async-tokio-template` and code away!

## Todos
- [ ] package versions are hardcoded
- [ ] Also include params for Cargo.toml in cookiecutter config
- [ ] Github template

# Flutter App Template
Template for Flutter apps, with development setups.

## Requirements
- Docker 27.3.1
- Docker Compose v2.29.7

## Dependencies
- Flutter

## Run on development mode
1. Set up docker container.
```bash
$ docker compose up
```

2. Enter docker container, and start the Flutter app.
- attaching the container to the terminal.
```bash
$ docker compose exec app bash && make start
```

- connecting to the container using `Dev Container` (VSCode extension).
  - connect to the container by "reopen in container"
  - exit to the local directory by "reopen file locally"
```bash
$ (devcontainer) make start
```

## Resources
- [Flutter documentation](https://docs.flutter.dev/)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

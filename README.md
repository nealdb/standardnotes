# StandardNotes & Docker

This repository contains all the configuration to generate the [StandardNotes](https://github.com/standardfile/ruby-server) Docker's image.

## Usage

- Build the image

```sh
docker build -t standardfile .
```

- Run the stack

```sh
docker-compose up -d
```

- Run the database migrations

```sh
docker exec -it standardfile_app bundle exec rails db:create db:migrate
```

## License

**MIT**

# docker-elixir-phoenix

## Usage

```
$ docker-compose build
$ docker-compose up -d
$ docker-compose run elixir bash -c "mix local.hex && mix archive.install https://github.com/phoenixframework/archives/raw/master/phoenix_new.ez"
$ docker-compose run --publish 80:4000 elixir bash -c "mix phoenix.server"
```

access to http://[HOST_MACHINE_IP]:4000

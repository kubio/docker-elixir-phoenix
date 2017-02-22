FROM elixir:1.4

RUN apt-get update && apt-get install -y nodejs npm && \
    npm update -g npm && \
    npm cache clean && \
    npm i -g n && \
    n 6.9.5

RUN mix local.hex &&\
    mix local.rebar &&\
    mix archive.install https://github.com/phoenixframework/archives/raw/master/phoenix_new.ez


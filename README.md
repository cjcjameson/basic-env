# Basic Environment

This repos sets up a basic Linux enviornment to interact with a bosh director.

## Usage

```
cd && git clone https://github.com/pivotal-cf-experimental/basic-env.git
. basic-env/.profile
new_env
exec $SHELL -l 
```

## What `new_env` sets up

1. Adds a `~/bin` dir and copies files in place
1. Installs some helpful tools:
    - ruby bundler 
    - bosh\_cli
    - Gnu Parallel - better xargs
    - jq - grep for json
    - ack - src code grepper


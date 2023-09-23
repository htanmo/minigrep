# Minigrep

A lightweight and simpler version of grep implemented in rust.

## How to use (without installing)

```sh
# running the application
> cargo run --release <query> <file-path>
```

## Installing the application

```sh
> cargo install --path . --locked
```

running after installing it

```sh
> minigrep <query> <filepath>
```

> note:
> make sure to run the following commands in the root directory

## Demo

`Command used : minigrep <query> <filepath>`

```sh
> minigrep to poem.txt
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```

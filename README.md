# Rust basic repository

This is a really basic rust repo to compile a "Hello fede" app

## Installation

Create the container and login into it to compile the project:


```bash

docker compose up -d
docker exec -it rust-hello-world bash

```

## Usage

Compile and run the project:

```bash

cd /workspace
cargo build
target/debug/hello_bbb

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
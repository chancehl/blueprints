# blueprints
Common blueprint-cli templates that I use

## Usage

1. Install Cargo / Rust:

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

2. Source your shell after installation

```
source "$HOME/.env/cargo"
```

3. Install [blueprint-cli](https://github.com/chancehl/blueprint-cli)

```
cargo install blueprint
```

4. Run blueprint `init` command

```
blueprint init
```

5. Clone this repository

```
git clone https://github.com/chancehl/blueprints
```

6. Call blueprint `make` command for whatever templates you'd like to use

```
blueprint make ./blueprints/[file-name].json
```

And then you're done!

# AETHER Reports

<!-- ## 📚 Resources -->

## 🛠️ Getting Started

There a few things here for you to settle:
1. Setup the Obsidian Vault
2. Setup the `uv` environment
3. Run `mkdocs`


### Obsidian

This repository is also stored as an Obsidian vault which you can use to access `.excalidraw` and `.canvas` files, which can be useful for drawing diagrams and illustrations for your sharings.

The `.obsidian/` directory is specifically loaded with the plugins for your use too.


### Setting Up Environment

This repository uses the `uv` environment management structure. You can install it [here](https://docs.astral.sh/uv/getting-started/installation/). After this, you can set up the virtual environment using the following command:

```sh
$ uv sync
```

This will install all the necessary dependencies for running this blog effectively.

### Serving Reports Locally

Since `uv` installs all the necessary dependencies, you can simply run the following command to serve the `mkdocs` system locally:

```sh
$ uv run mkdocs serve
```

This should allow you to run this blog locally.
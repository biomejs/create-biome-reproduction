# Create Biome Reproduction

Create a minimal project for reproducing issues with [Biome](https://biomejs.dev/).

The interactive CLI lets you choose a Biome version and package manager. It can
also initialize a Git repository and publish it to GitHub.

## Usage

Run the CLI with your preferred package manager:

```shell
npx @biomejs/create-biome-reproduction@latest

pnpm dlx @biomejs/create-biome-reproduction@latest

yarn dlx @biomejs/create-biome-reproduction@latest

bunx @biomejs/create-biome-reproduction@latest
```

Follow the prompts to choose:

- The project directory
- The Biome version to reproduce with
- The package manager to use
- Whether to initialize Git and create a public GitHub repository

The generated project includes a `biome.json` configuration, a placeholder
`src/index.ts`, and scripts for running `biome format`, `biome lint`,
`biome check`, and `biome ci`.

## Requirements

- Node.js 18, or Node.js 20 and later
- Git, when creating a repository
- [GitHub CLI](https://cli.github.com/), when publishing to GitHub

## License

This project is licensed under the [MIT license](LICENSE).

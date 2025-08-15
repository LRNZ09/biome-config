# @lrnz09/biome-config

Reusable Biome configuration for consistent formatting and linting across projects.

## Installation

Using `bun`:

```sh
bun add -D @lrnz09/biome-config
```

Using `npm`:

```sh
npm install -D @lrnz09/biome-config
```

## Usage

Create a `biome.json` in your project root:

```json
{
  "extends": ["@lrnz09/biome-config"]
}
```

## Features

- Automatic import organization on save
- Single quotes for both JS and JSX
- No semicolons unless required
- Git integration with `main` as default branch

## License

[MIT license](./LICENSE)

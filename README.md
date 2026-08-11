# Epitomos Documentation

Documentation for Epitomos, built on [Mintlify](https://mintlify.com).

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```
npm i -g mint
```

Run the following command at the root of this repo, where `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to docs.epitomos.com automatically after pushing to the `main` branch.

## Troubleshooting

- If your dev environment isn't running: run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: make sure you are running in a folder with a valid `docs.json`.

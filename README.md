# MagicPost documentation

This folder holds the MagicPost documentation, written for Mintlify. Navigation and branding live in `docs.json`, pages are `.mdx` files grouped by topic, and logos are in `logo/`.

## Preview locally

Install the Mintlify CLI, then run it from this folder:

```bash
npm i -g mint
mint dev
```

The preview opens at http://localhost:3000. Run `mint broken-links` to check internal links.

## Adding a page

1. Create the `.mdx` file with `title` and `description` in the frontmatter.
2. Add its path, without the extension, to the matching group in `docs.json`.

Plugin pages go in the `plugins/` folder, one `.mdx` per plugin, and are listed in the `Plugins` group in `docs.json` after `plugins/overview`.

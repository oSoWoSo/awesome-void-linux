# Extending Void Linux documentation

Guide to the Void Linux documentation ecosystem and how to contribute.

## Documentation projects

- The Void Linux Handbook (mdBook) - https://docs.voidlinux.org
- Handbook sources (void-docs) - https://github.com/void-linux/void-docs
- InfraDocs (Void systems management) - https://infradocs.voidlinux.org
- Void Linux manpages - https://man.voidlinux.org

## How the handbook works

The handbook is built with `mdbook` from the `void-docs` repository. Pages are Markdown files under `src/`. To propose changes, open a pull request against `void-linux/void-docs`.

## Contributing

- Contributing to Void (Handbook) - https://docs.voidlinux.org/contributing/index.html
- void-packages CONTRIBUTING - https://github.com/void-linux/void-packages/blob/master/CONTRIBUTING.md

## void-docs CLI

The `void-docs` utility provides local access to the handbook in several formats (man, html, pdf).

- void-docs(1) manpage - https://man.voidlinux.org/void-docs.1

## Tips

- Keep changes focused and follow existing style.
- Test the mdBook build locally before submitting.
- Update cross-references when adding or renaming pages.

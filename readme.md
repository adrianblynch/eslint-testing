# ESLint tests

Working out the hows and whys of ESLint.

I had questions about how config was used in root and sub folders so this highlights, to me anyway, how it works.

## Config files

All config files (.eslintrc) are read and used, with nested files overriding prior files.

## Interesting commands

- `DEBUG=eslint:* npm run lint`
- `DEBUG=eslint:cli-engine npm run lint`

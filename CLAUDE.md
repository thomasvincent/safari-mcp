# CLAUDE.md

Controls Safari from AI assistants via MCP -- manage tabs, windows, bookmarks, history, and reading list. Uses AppleScript on macOS.

## Tech Stack

- TypeScript, Node >=18, ES modules
- `@modelcontextprotocol/sdk`
- Vitest, ESLint 9 (flat config), Prettier

## Development

```sh
npm run build           # compile
npm test                # vitest run
npm run test:coverage   # with coverage
npm run lint            # eslint .
npm run format:check    # prettier check
```

## Repo Details

- Source and tests live under `src/` (`index.ts` + `__tests__/`)
- Husky pre-commit hooks enforce lint-staged (eslint + prettier on staged files)

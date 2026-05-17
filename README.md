# homebrew-ai-engineering-system

Homebrew tap for the [AI Engineering System](https://github.com/supanut9/ai-engineering-system).

## Install

```bash
brew install supanut9/ai-engineering-system/create-ai-engineering-system
```

## Use

```bash
create-ai-engineering-system --name my-app --stack nextjs-default --package-manager bun
```

The installed binary wraps the system's `init-project.sh`. See the [system docs](https://github.com/supanut9/ai-engineering-system) for flags and stacks.

## What it installs

- `bin/create-ai-engineering-system` — thin bash wrapper.
- `libexec/` — the full system tree (`scripts/`, `templates/skeletons/`, `claude/`, `codex/`, `tooling/`, etc.) at the tapped release tag.

Depends on `bash` (4+) and `git`.

## Updating

The formula pins to a specific `ai-engineering-system-v*` tag. To upgrade:

```bash
brew update
brew upgrade create-ai-engineering-system
```

## License

MIT.

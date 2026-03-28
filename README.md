# ai-token-optimizer

Portable **token-optimization** agent skill (markdown only). Host-agnostic: copy or symlink into your editor’s skills directory for the **repository you are working on**, or install globally if your client loads `~/.cursor/skills/`.

## Contents

- `.cursor/skills/token-optimization/SKILL.md` — main skill
- `.cursor/skills/token-optimization/reference.md` — deeper patterns and codex-tree CLI notes

## Use on this machine

**Option A — one project (recommended)**

From the git root of the repo you edit:

```bash
mkdir -p .cursor/skills
ln -sfn /ABS/PATH/TO/ai-token-optimizer/.cursor/skills/token-optimization \
  .cursor/skills/token-optimization
```

**Option B — Cursor user skills (all workspaces)**

```bash
mkdir -p ~/.cursor/skills
ln -sfn /ABS/PATH/TO/ai-token-optimizer/.cursor/skills/token-optimization \
  ~/.cursor/skills/token-optimization
```

Replace `/ABS/PATH/TO/ai-token-optimizer` with your clone path. If `token-optimization` already exists, remove or rename it first.

**Related:** [ai-dev-exp](https://github.com/sriramchandra-in/ai-dev-exp) bundles the same topic for **Cursor** plus CLI helpers (`ai-dev-exp install --cursor`).

## Repository

https://github.com/sriramchandra-in/ai-token-optimizer

## License

MIT — see [LICENSE](LICENSE).

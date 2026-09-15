# Geko Skills

Agent Skills that help agents work with [Geko](https://github.com/geko-tech/geko).

## Skills

| Skill | Purpose |
| --- | --- |
| `geko-migration` | Migrate existing iOS projects to Geko while preserving project behavior. |

## Install

Choose skills from the repository with either supported client:

```bash
npx skills add geko-tech/skills
```

```bash
gh skill install geko-tech/skills
```

To install a specific skill:

```bash
npx skills add geko-tech/skills --skill geko-migration
```

```bash
gh skill install geko-tech/skills geko-migration
```

To install a specific skill from a pinned repository release:

```bash
npx skills add 'geko-tech/skills#0.1.0' --skill geko-migration
```

```bash
gh skill install geko-tech/skills geko-migration@0.1.0
```

## Distribution

- Skills follow the [Agent Skills specification](https://agentskills.io/specification).
- This repository is the source of truth for all skill files.
- `npx skills` and `gh skill` install the same skills directly from the
  repository.
- The repository is versioned as a single package using SemVer tags such as
  `0.1.0` and matching GitHub Releases.
- Pull requests validate the skills; releases are created manually after
  merging to `main`.

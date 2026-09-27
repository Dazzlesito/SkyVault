# TeamDrive

> Short description of the project — replace this line.

## Getting Started

```bash
git clone https://github.com/Dazzlesito/TeamDrive.git
cd TeamDrive
```

## GitHub Flow

This repo uses a simplified [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow):

1. **`main` is always deployable.** You cannot push directly to it — it is protected.
2. **Create a branch** from `main` for every piece of work:
   ```bash
   git checkout main
   git pull origin main
   git checkout -b your-branch-name
   ```
3. **Commit often** with clear messages:
   ```bash
   git add -A
   git commit -m "Add: short description of the change"
   ```
4. **Push and open a Pull Request** early:
   ```bash
   git push -u origin your-branch-name
   gh pr create --fill
   ```
5. **Get review + passing checks**, then merge. Delete the branch after merging.

### Commit message convention

| Prefix    | Use for                          |
| --------- | -------------------------------- |
| `Add:`    | New files or features            |
| `Update:` | Changes to existing code         |
| `Fix:`    | Bug fixes                        |
| `Docs:`   | Documentation only               |
| `Refactor:` | Restructuring without behavior change |

## Collaborators

| Name | GitHub |
| ---- | ------ |
| Andrés Cortés | [@Dazzlesito](https://github.com/Dazzlesito) |
| Classmate 1 | _TBD_ |
| Classmate 2 | _TBD_ |

## TODO

- [ ] Decide project stack
- [ ] Add CI workflow (`.github/workflows/`)
- [ ] Enable required status checks on `main`
- [ ] Add collaborators:
      `gh api -X PUT repos/Dazzlesito/TeamDrive/collaborators/USERNAME -f permission=push`

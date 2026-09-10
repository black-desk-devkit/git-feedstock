# git-feedstock

Conda feedstock for [Git](https://git-scm.com/).

Builds Git for `linux-64` and `osx-arm64`, including manpages, HTML docs,
bash completion, and the `git subtree` and `git contacts` contrib commands.

## Update procedure

1. Bump `version` in `recipe/recipe.yaml`
2. Update the source `sha256` sums
3. Reset `build.number` to `0` on version bumps
4. Commit to `main` — CI builds and uploads to
   [prefix.dev/black-desk](https://prefix.dev/black-desk)

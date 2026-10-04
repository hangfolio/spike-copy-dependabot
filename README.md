# spike-copy-dependabot

Throwaway design spike for hangfolio (spike S7). A copy of `hangfolio/spike-template`, pushed as one
commit, with two changes that give Dependabot something to propose:

- `package.json` pins `kleur` at the outdated exact version 4.0.0. It stands in for the theme package,
  and `.github/dependabot.yml` allows only it.
- `.github/workflows/s7-aged-engine.yml` calls `hangfolio/spike-engine-aged` at `v1`, whose `v2` is
  dated older than Dependabot's default cooldown. `deploy.yml` still calls `hangfolio/spike-engine` at `v1`.

No repository setting was changed. GitHub Pages is off. Example content only. This repository will be archived.

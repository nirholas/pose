# AGENTS.md

Guidance for AI coding agents working in, or using, this repository.

## What this is

`@three-ws/pose`: Deterministic, named pose seeds for rigged 3D avatars. Map a natural-language prompt to a stable seed + full Euler joint-rotation map from the three.ws pose-studio preset library.

Part of [three.ws](https://three.ws). Canonical docs: [README.md](README.md). Machine-readable summary: [llms.txt](llms.txt).

## Work on it

```bash
npm install
npm test
```

Rules:

- Read the README and the neighboring code before changing anything; match the existing style.
- Every behavior change gets a test. Tests use real inputs, no network calls unless the package is a client for one.
- Never commit secrets, private keys or real wallet material.
- Keep the public API in the README accurate: update it in the same change.
- Use plain, specific commit messages (`fix(scope): what changed and why`).

## Discovery

- Site: https://nirholas.github.io/pose/
- npm: https://www.npmjs.com/package/@three-ws/pose
- Platform: https://three.ws

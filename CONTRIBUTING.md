# Contributing

Thank you for your interest in contributing to **Lernex**!  
This project grows and thrives through open-source collaboration, and we’re excited to have you join our journey 🚀

##  Before You Start

Please take a few minutes to:
- Read this [contributing guide](./CONTRIBUTING.md) carefully.  
- Review any open [Issues](https://github.com/2MJ-DEV/Lernex/issues).  
- Join the discussion before starting new work (so efforts don’t overlap).  

If you’re new to open source, don’t worry — we welcome developers of **all experience levels**.  
Even fixing a typo, improving documentation, or sharing feedback makes a real difference ❤️

## About this repository

This repository is a monorepo.

- We use [pnpm](https://pnpm.io) and `workspaces` for development.
- We use [Turborepo](https://turbo.build/repo) as our build system.
- We use [changesets](https://github.com/changesets/changesets) for managing releases.

## Structure

This repository is structured as follows:
```
```

## How to Contribute (Step-by-Step)

1. **Fork** the repository  
2. **Clone** your fork  
   ```bash
   git clone https://github.com/2MJ-DEV/Lernex.git
   ```
3. **Create a branch** for your feature or fix
```bash
git checkout -b feature/my-new-feature
```
4. **Commit** your changes with a clear message
```bash
git commit -m "[Add]: New module about Next.js routing"
```
5. **Push**  to your fork
```bash
git push origin feature/my-new-feature
```

6. **Open a Pull Request (PR)** on the main repository
   - Include a short description of your changes
   - Reference related issues (if any)
  
## Commit Convention

Before you create a Pull Request, please check whether your commits comply with
the commit conventions used in this repository.

When you create a commit we kindly ask you to follow the convention
`category(scope or module): message` in your commit message while using one of
the following categories:

- `feat / feature`: all changes that introduce completely new code or new
  features
- `fix`: changes that fix a bug (ideally you will additionally reference an
  issue if present)
- `refactor`: any code related change that is not a fix nor a feature
- `docs`: changing existing or creating new documentation (i.e. README, docs for
  usage of a lib or cli usage)
- `build`: all changes regarding the build of the app, changes to
  dependencies or the addition of new dependencies
- `test`: all changes regarding tests (adding new tests or changing existing
  ones)
- `ci`: all changes regarding the configuration of continuous integration (i.e.
  github actions, ci system)
- `chore`: all changes to the repository that do not fit into any of the above
  categories

  e.g. `feat(components): add new prop to the avatar component`

## Exécuter le projet Odin localement
Follow our [instructions on running The Odin Project locally](#). These instructions include all installations you will need as well as optional instructions for setting up authentication.

## Adding Curriculum Content

When new content is ready to be or has already been merged in the Lernex curriculum repo, the web app must be updated to render that new content. The following instructions cover how to add new curriculum content to the web app, but you can also refer to them when editing existing content:

- [Adding a lesson](#)
- [Adding a section](#)
- [Adding a course](#)
- [Adding a path](#)

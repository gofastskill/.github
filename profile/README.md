# FastSkill

Package manager and operational toolkit for Agent AI Skills.

[![CI](https://github.com/gofastskill/fastskill/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/gofastskill/fastskill/actions/workflows/test.yml)
[![codecov](https://codecov.io/gh/gofastskill/fastskill/branch/main/graph/badge.svg)](https://codecov.io/gh/gofastskill/fastskill)

FastSkill helps teams install, organize, and operate AI skills with reproducible workflows.

## Core value

- Manage skill dependencies with `skill-project.toml` and `skills.lock`
- Install from local, git, and registry sources
- Search skills across remote catalogs or local installs
- Validate and evaluate skills before shipping
- Sync installed skills into agent metadata files

## Quick start

```bash
fastskill -V
fastskill init
fastskill add ./skills/my-skill -e --group dev
fastskill install
fastskill list
```

## Learn more

- Repository: [gofastskill/fastskill](https://github.com/gofastskill/fastskill)
- Quick start: [webdocs/quickstart.mdx](https://github.com/gofastskill/fastskill/blob/main/webdocs/quickstart.mdx)
- Installation: [webdocs/installation.mdx](https://github.com/gofastskill/fastskill/blob/main/webdocs/installation.mdx)
- CLI reference: [webdocs/cli-reference/overview.mdx](https://github.com/gofastskill/fastskill/blob/main/webdocs/cli-reference/overview.mdx)

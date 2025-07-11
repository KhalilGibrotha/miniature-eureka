# Documentation

## CI Workflow Overview

The CI pipeline runs linting, security scans, Ansible tests and documentation checks on every push or pull request.

## Directory Layout

- `playbooks/` - example Ansible playbooks
- `src/` - Python package
- `docs/` - project documentation

## Local Checks

Install requirements from `requirements.txt` and run the same linters locally:

```bash
pip install -r requirements.txt
flake8 .
black --check .
yamllint .
ansible-lint playbooks/hello.yml
```


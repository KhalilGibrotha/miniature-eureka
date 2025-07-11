# miniature-eureka

[![CI](https://github.com/OWNER/miniature-eureka/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/OWNER/miniature-eureka/actions/workflows/ci.yml)

A minimal Ansible project with CI pipeline.

## Usage

```bash
# Clone the repository
git clone https://github.com/OWNER/miniature-eureka.git
cd miniature-eureka

# Playbooks live in the playbooks/ directory

# Install dependencies
pip install -r requirements.txt

# Run lint and tests locally
flake8 .
black --check .
yamllint .
ansible-lint playbooks/hello.yml
```

More documentation is available in the [docs](docs/) folder.

## Contributing

Please open an issue or pull request to contribute.


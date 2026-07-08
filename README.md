# Jerry Smith Personal Domain

| Check | Status |
| --- | --- |
| CI | [![CI](https://github.com/dean1012/personal-web/actions/workflows/ci.yml/badge.svg)](https://github.com/dean1012/personal-web/actions/workflows/ci.yml) |
| Production | [![Prod Deploy](https://github.com/dean1012/personal-web/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/dean1012/personal-web/actions/workflows/deploy.yml?query=branch%3Amain) |
| Development | [![Dev Deploy](https://github.com/dean1012/personal-web/actions/workflows/deploy.yml/badge.svg?branch=dev)](https://github.com/dean1012/personal-web/actions/workflows/deploy.yml?query=branch%3Adev) |

This repository contains the source code to my personal domain. It is public
for transparency and review.

This repository does not contain sensitive data.

## Table of Contents

- [Scope](#scope)
- [Contributing](#contributing)
- [License](#license)

## Scope

- Maintain my public personal domain.
- Store deployable static frontend content under `site/frontend/`.
- Validate website HTML, CSS, JavaScript, YAML, and Markdown through GitHub
  Actions.

Continuous deployment is managed through GitHub repository variables and
secrets. See the
[hosted-domain repository setup](https://github.com/dean1012/grayhaven-vault-example/blob/main/docs/setup.md#set-up-hosted-domain-repositories)
documentation in `grayhaven-vault-example` for the required deployment
settings.

This repository is not a general-purpose website template. Reusing this
repository for another website requires review, adaptation, and separate
branding.

[Back to top](#jerry-smith-personal-domain)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for development setup, validation
commands, and contribution guidelines.

[Back to top](#jerry-smith-personal-domain)

## License

[MIT](LICENSE)

[Back to top](#jerry-smith-personal-domain)

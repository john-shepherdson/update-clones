# UPDATE-CLONES

This repository contains a script to synchronises multiple Git repositories
for the purposes of SQA via SonarCloud. This is done by:

- Cloning them from 3rd party GitHub locations if they do not exist locally
- Detecting whether the remote uses `master` or `main`
- Pulling updates from a source repository path using rebase
- Force-pushing the result to a personal GitHub using --force-with-lease

## Prerequisites

- Git installed and configured.
- `repos` array populated with local or remote repository paths.

## Usage

./update-clones.bsh [--dry-run]

## Options

--dry-run    Print commands without executing them

## Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

See [Semantic Versioning](https://semver.org/) for guidance.

## Contributors

You can find the list of contributors in the [CONTRIBUTORS](CONTRIBUTORS.md) file.

## License

See the [LICENSE](LICENSE.txt) file.

## CITING

See the [CITATION](CITATION.cff) file.

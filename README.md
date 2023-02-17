# lerna-ci-cd-example - Forked!

An example of a package-based monorepo using Lerna, complete with autonomous CI and CD with Github Actions.

**This is a fork of the original repo, so it cannot successfully run the Version or Publish workflows, as it does not have access to the necessary secrets from the original.**

## Contributing

Below are some commands to run for common tasks within the monorepo.

- `lerna run build` - Build all packages
- `lerna run test` - Run all unit tests

### Requires Elevated privileges

- `lerna version` - Bump version of all packages changed since last version
- `lerna publish from-git` - Publish packages marked for release by the most recent version tag

## References

See [References](./REFERENCES.md) for resources used to create this example.

# test-puppet-module

## Test `bolt module install` with Bolt project that uses a Git module that has a pre-release version in metadata.json.

It turns out that it is the known issue [Versions in metadata.json do not follow the semver specification](https://github.com/puppetlabs/bolt/issues/3214).

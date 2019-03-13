# `cci-orbs` Overview

The `cci-orbs` GitHub organization contains all of the official `circleci` namespaced orbs.
Partner and community orbs should not be located in this GitHub org.
This GitHub org is maintained by the CircleCI Community & Partner Engineering Team.


## Structure

Each repository is an orb. The repository name should be the orb's name under the `circleci` namespace.
For example, the Hugo orb's full name is `circleci/hugo` and it's repository is `github.com/cci-orbs/hugo`.


## Contributing

Each orb has its own repository.
Please find the repository for the orb in question, and then open a GitHub Issue or Pull Requests in that repository.
GitHub Issues shouldn't be used for general orb support, see [resources](#resources).


### Creating New Repositories/Orbs

1. The CPE Team should be added as admin.
1. Force status checks should be enabled for `master`.
1. Protect from pushing to `master` directly.
1. Turn off Wiki/Projects for the repo.


## Resources

[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.
[Orb Discussion](https://discuss.circleci.com/c/orbs) - The Orbs category on CircleCI Discuss, our forum. This should be used for general orbs questions and support.
[Orb Development orb](https://circleci.com/orbs/registry/orb/circleci/orb-tools) - The `circleci/orb-tools` provides resources to create, test, and publish your own orbs.

## Deprecated Projects

This repository contains copies of deprecated projects that are no longer maintained by the Hydra community.

#### Why do we deprecate projects?

Out dated projects have been a source of confusion for new adopters who stumble upon them, not realizing they are no longer maintained.

#### When do we deprecate projects?

1. First we identify a project that is no longer being maintained by the Hydra community.
1. Then we send an announcement to the hydra-tech mailing list (hydra-tech@googlegroups.com) that the project is slated for deprecation.
1. If there is no request to keep the project active, then the repository is compressed and added to the `deprecated-projects` repository.
1. The repository containing the deprecated project is then deleted from github.

#### How do we deprecate projects?

1. The repository containing the project to be deprecated is cloned from github as is.
1. The `origin` remote is removed.
1. The repository is compressed to `.zip` and/or `.tgz` and added to the `deprecated-projects` repository in a directory of the same name as the deprecated project.

#### How do you retrieve a deprecated project?

1. Go to https://github.com/projecthydra/deprecated-projects.
1. Locate the directory containing the compressed repositories of the deprecated project (they are all named the same as the project at the time it was deprecated).

#### How do we ressurect a project?

Send a request to the hydra-tech mailing list (hydra-tech@googlegroups.com).
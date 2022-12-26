# Boilerplate Builder for EBBS

This builder creates all the necessary code for using [EBBS](https://github.com/eons-dev/bin_ebbs) and [the associated Github Actions](https://github.com/eons-dev/part_ebbs-workflows) to manage the devops of your repository.

The goal in using this setup is:
1. Make it easier for you to write your code, no matter what that code is.
2. Make devops simple and use a "set it and forget it" style pipeline.
3. Keep your repository focused by removing the need for lots of ops-related files.

## Usage

Getting started with this boilerplate is easy: just run:
```
ebbs -b boilerplate --name "name_of_project" --type "type_of_project"
```
from your, preferably empty, repository.

Here, `name` is what you'd like to call your codebase and `type` is how you'd like to treat that codebase. For example a `type` of `exe` might mean you intend to publish a standalone executable to some repository, while a `type` of `lib` might mean your code should be consumed by other `lib`s and `exe`s but is not meant to be run on its own.

**NOTE: This will not create your repository for you (i.e. the .git folder is not touched).**
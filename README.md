# Hook Test

Testing different git hook managers:

* [Husky](https://github.com/typicode/husky)
  * 31.1k stars
  * written in: node
  * pros:
    * seems to be the defacto choice for the JS world
  * cons:
    * must use js package manager to install, not available in brew and doesn't
      work without node
    * no parallel execution
    * seems like it requires a `package.json` in the root of the repo
* [quickhook](https://github.com/dirk/quickhook)
  * 54 stars
  * written in: go
  * pros:
    * install with brew (via a tap), deb and rpm available
    * supports running hooks in parallel
* [lefthook](https://github.com/evilmartians/lefthook)
  * 3.7k stars
  * written in: go
  * pros:
    * installable with a [lot of package managers](https://github.com/evilmartians/lefthook/blob/master/docs/install.md)
      including npm, gem, brew, deb, rpm...
    * supports running hooks in parallel
* [Autohook](https://github.com/Autohook/Autohook)
  * stars: 135
  * written in: shell
  * pros:
    * fully self contained, commit autohook.sh to the repo, no other dependencies
  * cons:
    * no colors
    * no parallel hook execution
* [pre-commit](https://github.com/pre-commit/pre-commit)
  * 11.7k stars
  * written in: python
  * pros:
    * seems fairly mature
  * [installable with brew](https://pre-commit.com/#install)
  * supports running hooks in parallel
  * cons:
    * python is annoying
* [githooks](https://github.com/gabyx/githooks)
  * 90 stars
  * written in: go
  * pros:
    * seems robust
  * cons:
    * install procedure appears to be: download tar.gz off github releases. no
      brew or anything.
* [githooks](https://github.com/rycus86/githooks)
  * 369 stars
  * written in: shell
  * pros:
    * install is trivial: script is checked into the repo itself

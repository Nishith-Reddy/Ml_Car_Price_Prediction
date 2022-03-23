## Included Software: Xenial

This is the **Xenial** build image. It runs on Ubuntu version 16.04 (aka Xenial), and includes the languages and software versions listed below.

For instructions on how to run this image locally to test your build, please see the [README](/README.md).

### Languages

The specific patch versions included will depend on when the image was last built (except Ruby). It is highly suggested you depend only on minor versions, so that we can ensure the language has the latest updates (especially if security related).

* Ruby - `RUBY_VERSION`, `.ruby-version`
  * 2.6.2 (default)
  * Any version that `rvm` can install.
* Node.js - `NODE_VERSION`, `.nvmrc`, `.node-version`
  * 10 (default)
  * Any version that `nvm` can install.
* Python - `runtime.txt` or `Pipfile`
  * 2.7 
  * 3.5
  * 3.7
  * 3.9 (default)

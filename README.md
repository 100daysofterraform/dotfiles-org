# Organization-specific Dotfiles for @planapply

> This repository is a collection of organization-specific `dotfiles` for [@planapply](https://github.com/planapply/).

## Table of Contents

- [Organization-specific Dotfiles for @planapply](#organization-specific-dotfiles-for-planapply)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
  - [Usage](#usage)
  - [Notes](#notes)
  - [Author Information](#author-information)
  - [License](#license)

## Background

The contents of this repository constitute the organization-specific configuration that is used during development and maintenance of [@planapply](https://github.com/planapply/) projects.

The contents of this `dotfiles-org` repository are expected to be on the same level as a project's main directory:

```sh
.
|-- dotfiles-org
|-- backlot
|-- website-backend
|-- website-frontend
`--  website-redirects
```

## Usage

Clone this repository, preserving the original directory name:

```sh
git clone git@github.com:planapply/dotfiles-org.git ./dotfiles-org
```

## Notes

The projects that consume this repository's contents (`dotfiles-org`) do not depend on a full Git history. That is to say: it is perfectly fine to make a shallow clone, using the `--depth=1` option.

## Author Information

This repository is maintained by the contributors listed on [GitHub](https://github.com/planapply/dotfiles-org/graphs/contributors).

Original code in this repository was developed for [operatehappy/dotfiles-org](https://github.com/operatehappy/dotfiles-org) and is used with permission.

## License

Licensed under the Apache License, Version 2.0 (the "License").

You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an _"AS IS"_ basis, without WARRANTIES or conditions of any kind, either express or implied.

See the License for the specific language governing permissions and limitations under the License.

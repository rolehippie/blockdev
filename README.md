# blockdev

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/blockdev) [![Testing Build](https://github.com/rolehippie/blockdev/workflows/testing/badge.svg)](https://github.com/rolehippie/blockdev/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/blockdev/workflows/readme/badge.svg)](https://github.com/rolehippie/blockdev/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/blockdev/workflows/galaxy/badge.svg)](https://github.com/rolehippie/blockdev/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/blockdev)](https://github.com/rolehippie/blockdev/blob/master/LICENSE)

Ansible role to configure readahead values for disks.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Default Variables](#default-variables)
  - [blockdev_definitions](#blockdev_definitions)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### blockdev_definitions

List of block devices to manipulate

#### Default value

```YAML
blockdev_definitions: []
```

#### Example usage

```YAML
blockdev_definitions:
  - device: /dev/vdb
    ra: 32
```

## Discovered Tags

**_blockdev_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)

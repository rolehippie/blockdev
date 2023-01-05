# blockdev

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/blockdev) [![General Workflow](https://github.com/rolehippie/blockdev/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/blockdev/actions/workflows/general.yml) [![Readme Workflow](https://github.com/rolehippie/blockdev/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/blockdev/actions/workflows/readme.yml) [![Galaxy Workflow](https://github.com/rolehippie/blockdev/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/blockdev/actions/workflows/galaxy.yml) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/blockdev)](https://github.com/rolehippie/blockdev/blob/master/LICENSE) ![Ansible Role](https://img.shields.io/ansible/role/51419)

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

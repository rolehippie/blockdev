# blockdev

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/blockdev) [![Build Status](https://img.shields.io/drone/build/rolehippie/blockdev/master?logo=drone)](https://cloud.drone.io/rolehippie/blockdev) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/blockdev)](https://github.com/rolehippie/blockdev/blob/master/LICENSE) 

Ansible role to configure readahead values for disks. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [blockdev_definitions](#blockdev_definitions)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

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

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)

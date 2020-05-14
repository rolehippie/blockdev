# blockdev

[![Build Status](https://cloud.drone.io/api/badges/rolehippie/blockdev/status.svg)](https://cloud.drone.io/rolehippie/blockdev)

Ansible role to configure blockdev

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

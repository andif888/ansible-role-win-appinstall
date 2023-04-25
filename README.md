# ansible-role-win-appinstall

Role to install apps on windows pointing to a download url.

Checkout [test.yml](./tests/test.yml) for example usage.

## Table of content

- [Default Variables](#default-variables)
  - [win_appinstall_download_dir](#win_appinstall_download_dir)
  - [win_appinstall_download_force](#win_appinstall_download_force)
  - [win_appinstall_url](#win_appinstall_url)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### win_appinstall_download_dir

Download directory

#### Default value

```YAML
win_appinstall_download_dir: C:\windows\temp\win_appinstall
```

### win_appinstall_download_force

orce download, also when file already exists

#### Default value

```YAML
win_appinstall_download_force: false
```

### win_appinstall_url

Download URL

#### Default value

```YAML
win_appinstall_url: ''
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888

<h1 align="center"><strong>Pterodactyl AutoInstaller</strong></h1>

- Install Panel
- Install Wings
- Install Panel & Wings
- Install PHPMyAdmin
- Uninstall PHPMyAdmin
- Switch Pterodactyl Domains
- Uninstall Panel
- Uninstall Wings
- Autoinstall [ONLY NGINX & BETA]

# Supported OS & Webserver
Supported operating systems.

| Operating System | Version               | Supported                          |   PHP |
| ---------------- | ----------------------| ---------------------------------- | ----- |
| Ubuntu           | from 20.04 to 24.04   | :white_check_mark:                 | 8.3   |
| Debian           | from 11 to 12         | :white_check_mark:                 | 8.3   |
| CentOS           |       centos 7        | :white_check_mark:                 | 8.3   |
| Rocky Linux      | no supported versions | :x:                                | :x:   |

:warning: Be aware of using CentOS 7. It is EOL and there will not be added support in this script for any newer CentOS version. If you are running CentOS and you want to use this script, you should switch to a new distro, such as Debian or Ubuntu.

| Webserver        | Supported           |
| ---------------- | --------------------| 
| NGINX            | :white_check_mark:  |
| Apache           | :white_check_mark:  |
| LiteSpeed        | :x:                 |
| Caddy            | :x:                 |

# Contributors
Copyright 2022-2023, [Malthe K](https://github.com/guldkage), me@malthe.cc
<br>
Created and maintained by [Malthe K.](https://github.com/guldkage)

### Required fields
```
<fqdn> = What you want to access your panel with. Eg. panel.domain.ltd
```

You must be precise when using this script. 1 typo and everything can go wrong.
It also needs to be run on a fresh version of Ubuntu or Debian.

```bash
bash <(curl -s https://raw.githubusercontent.com/guldkage/Pterodactyl-Installer/main/autoinstall.sh) <fqdn>
```

# WIDE PROOT DISTRO
q. why did you name it like that?<br>
a. idk

this is just a wrapper with some quality of life features for [Proot-Distro](https://github.com/termux/proot-distro)

### installation
```
curl -sS https://raw.githubusercontent.com/Welpyes/wide-proot-distro/refs/heads/master/install | sh
```
<b>Usage: wpd [OPTIONS]</b>
```
Options:
  useradd {user}             Add a user to be invoked later.

  userdel                    Remove the saved user.

  -d, --distro {distro}      Select a distro to login with.

  -su, --select-user {user}  Log in with the specified user
                             in the selected distro.

  i, install {distro}        Install the specified distro.

  rm, remove {distro}        Remove the specified distro.

  rs, reset {distro}         Reset the specified distro.

  ls, list                   List all available distros.

  cl, clear                  Clear proot-distro cache.

  mv, rename {distro}        Rename the specified distro.

  restore {path}             Restore a distro from a file.

  bk, backup {distro} {path} Backup the specified distro to a file.

  uninstall                  Uninstall wpd (and optionally proot-distro).

  --verbose                  Enable verbose logging.

  --help                     Show this help message.

Examples:
  wpd useradd welpyes
  wpd userdel
  wpd -d fedora
  wpd -d fedora --su welpyes
  wpd i fedora
  wpd rm ubuntu
  wpd rs debian
  wpd ls
  wpd cl
  wpd mv fedora
  wpd restore /path/to/file
  wpd bk debian /path/to/backup.tar.gz
  wpd uninstall
  wpd uninstall -rf
```

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

  -su, --select-user {user} Log in with the specified user
                            in the selected distro.

  i, install {distro}      Install the specified distro.

  rm, remove {distro}      Remove the specified distro.

  rs, reset {distro}       Reset the specified distro.

  ls, list                 List all available distros.

  --help                   Show this help message.

Examples:
  prssh useradd welpyes
  prssh userdel
  prssh -d fedora
  prssh -d fedora --su welpyes
  prssh -d fedora --su root
  prssh i fedora
  prssh rm fedora
  prssh rs fedora
  prssh ls
```

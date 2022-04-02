# Lutris

**Lutris** helps you install and play video games from all eras and from most gaming systems. By leveraging and combining existing emulators, engine re-implementations and compatibility layers, it gives you a central interface to launch all your games.

The client can connect with existing services like Humble Bundle, GOG and Steam to make your game libraries easily available. Game downloads and installations are automated and can be modified through user made scripts.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/lutris
$ dnf install -y lutris
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y lutris
```

## Remove

```
$ dnf erase -y lutris
$ dnf copr remove pkgstore/lutris
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/lutris).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/lutris) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.

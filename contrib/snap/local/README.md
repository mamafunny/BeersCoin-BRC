# Beerscoin Snap Packaging

Commands for building and uploading a Beerscoin Core Snap to the Snap Store. Anyone on amd64 (x86_64), arm64 (aarch64), or i386 (i686) should be able to build it themselves with these instructions. This would pull the official Beerscoin binaries from the releases page, verify them, and install them on a user's machine.

## Building Locally
```
sudo apt install snapd
sudo snap install --classic snapcraft
sudo snapcraft
```

### Installing Locally
```
snap install \*.snap --devmode
```

### To Upload to the Snap Store
```
snapcraft login
snapcraft register beerscoin-core
snapcraft upload \*.snap
sudo snap install beerscoin-core
```

### Usage
```
beerscoin-unofficial.cli # for beerscoin-cli
beerscoin-unofficial.d # for beerscoind
beerscoin-unofficial.qt # for beerscoin-qt
beerscoin-unofficial.test # for test_beerscoin
beerscoin-unofficial.tx # for beerscoin-tx
```

### Uninstalling
```
sudo snap remove beerscoin-unofficial
```
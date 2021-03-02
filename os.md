## OS Selection

### Requirements

-   Good Docker Host
    -   NVENC Pass-through
-   Can run ZFS storage drives
-   Can run BTRFS or ZFS root partition (or some other root partition recovery scheme)
-   IaC compatible
-   Pi / ARM compatible(?)
-   Package manager can be hooked to run snapshots (if relevant)
-   Will be around in 10 years(?)
-   Relatively quick updates
-   Root FS encryption

### Possibilities

-   [Manjaro](https://manjaro.org/downloads/official/architect/)
-   [Arch](https://archlinux.org/)
-   [CentOS Stream](https://www.centos.org/centos-stream/)
-   [openSUSE Leap](https://www.opensuse.org/#Leap)
-   [Rocky Linux](https://rockylinux.org/)
    Not released as of 2021-03
-   [Fedora CoreOS](https://getfedora.org/coreos?stream=stable)
-   [FlatCar Linux](https://kinvolk.io/flatcar-container-linux/)
-   [NixOS](https://nixos.org/)

### Requirements matrix

| OS                | Docker | NVENC | ZFS | root snapshotting | IaC | Pi  | Snapshot hook for PM | 10+ year lifespan | Quick Updates | Root FS Enc |
| ----------------- | ------ | ----- | --- | ----------------- | --- | --- | -------------------- | ----------------- | ------------- | ----------- |
| Manjaro           | 9      | 10    | 8   | 9                 | 10  | 8   | 9                    | 8                 | 7             | 6           |
| Arch              | 9      | 10    | 8   | 9                 | 10  | 9   | 9                    | 10                | 10            | 7           |
| ~~CentOS Stream~~ | 9      | 10?   |     |                   | 10  |     | 9                    | 7                 | 7             |             |
| OpenSUSE Leap     | 9      | 10?   | 8   | 10                | 10  | 9   | 10                   | 10                | 5             | 7           |
| ~~Fedora CoreOS~~ | 10?    |       |     |                   |     |     |                      |                   |               |             |
| ~~FlatCar Linux~~ | 10?    |       | 0   |                   |     |     |                      |                   |               |             |
| ~~NixOS~~         |        | 6     |     |                   | 10  | 9   |                      |                   |               |             |

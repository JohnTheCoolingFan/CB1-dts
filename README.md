# BTT CB1 dts collection

This repo contains known variants of device tree source files for BigTreeTech Pi and CB1. The purpose of the repository is to have a place to quickly compare device trees to improve device trees for btt-cb1

Current item of focus is ethernet (emac1)

| dir name                   | description                                      | source                                                                               |
|----------------------------|--------------------------------------------------|--------------------------------------------------------------------------------------|
| `armbian-sunxi-6.6`        | Armbian dts from `./compile.sh kernel-dtb <...>` | https://github.com/JohnTheCoolingFan/armbian-build/tree/btt-cb1                      |
| `btt-kernel-5.16`          | dts by BigTreeTech                               | https://github.com/bigtreetech/CB1-Kernel                                            |
| `linux-mainline/linux-6.7` | dts from mainline linux 6.7                      | https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/tree/?h=linux-6.7.y |
| `linux-mainline/linux-6.9` | dts from mainline linux 6.9                      | https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/tree/?h=linux-6.9.y |

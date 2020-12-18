# PX Chromium output directory
This repository is for versioning the `args.gn` files for various Chromium configurations.

## Instructions
Clone this repo to the `src/out` directory.
```shell
cd src
git clone https://github.com/bbc/px-chromium-out.git out
```
Generate output files for your desired configuration, for example `Ozone_ARM_RPi_Release`:
```shell
gn gen out/Ozone_ARM_RPi_Release
```

## Configuration names
Configurations should be named with the platform, target architecture, target device, release/debug and any other notable settings in the `args.gn` file.

## About
Maintained by Ewan Roycroft <<ewan.roycroft@bbc.co.uk>>

More information on the [PX Confluence pages](https://confluence.dev.bbc.co.uk/display/PLATFORMEX).

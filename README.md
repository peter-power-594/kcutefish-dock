# Dock

CutefishOS application dock.

## OpenMandriva Dependencies

```shell
sudo dnf in task-develop
sudo dnf install lib64Qt5QuickControls2-devel kwindowsystem-x11
```

You also need [`fishui`](https://github.com/peter-power-594/kcutefish-fishui) and [`libcutefish`](https://github.com/peter-power-594/kcutefish-libcutefish).

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.

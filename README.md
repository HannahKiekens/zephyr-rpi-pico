
Start development environment with:

```
./zephyr-container
```

Initialize environment and build

```
west init -l rpi-pico-hello/
west build --pristine -b rpi_pico rpi-pico-hello/app
```
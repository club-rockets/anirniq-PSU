# Power Supply Unit submodule

Power supply unit supervisor for anirniq submodules and recovery system

## Features

  - CAN interface
  - I2C interface for current monitoring
  - Low noise Buck converter (3.3V and 5V)
  - Connector for batterie input (max 18V)

## Project repository

https://github.com/club-rockets/anirniq-PSU

## Dependency

- STCubeMX
- Atollic TrueSTUDIO IDE
- gcc
- make

## Build

Use cmake to build the project

```bash
make
```

To clean the project

```bash
make clean
```

## Project pinout
| PIN NAME | PIN NUMBER |
| ------ | ------ |
|CAN1 STANDBY | PA10|
|CAN1 RX | PA11|
|CAN1 TX | PA12|
|I2C SCL | PA15|
|I2C SDA | PB7|
|LED1 | PA4|
|LED2 | PA5|
|LED3 | PA6|
|LED4 | PA7|

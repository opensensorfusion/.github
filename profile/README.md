# Open Sensor Fusion

Open Sensor Fusion is an open hardware project for sensor aggregation devices
and Linux IIO host support.

The first hardware target is OSF GREEN, an STM32F405-based prototype board with
an ICM42688P-class IMU and MMC5983MA magnetometer. The current Linux RFC path
uses an OSF0 UART frame stream from the board to a host.

## Repositories

- `opensensorfusion-hardware` - OSF GREEN hardware design files and
  documentation
- `opensensorfusion-firmware` - firmware for Open Sensor Fusion hardware
  targets
- `opensensorfusion-linux` - Linux IIO driver and host-side documentation

## Scope

- open hardware sensor aggregation devices
- host interface documentation
- Linux IIO support

The Linux RFC does not define USB/Web demo output, calibration sysfs, yaw debug
frames, or fusion/AHRS/Kalman output.

# Data Format

## Vibration Channel

The MPU6050 data will contain:

- timestamp
- sample index
- acceleration X
- acceleration Y
- acceleration Z
- gyroscope X
- gyroscope Y
- gyroscope Z

Example:

timestamp,sample,ax,ay,az,gx,gy,gz

## Acoustic Channel

The INMP441 data will contain:

- timestamp
- sample index
- audio amplitude/sample value

Example:

timestamp,sample,audio

## Window

Sensor data will be divided into fixed-length windows.

Initial target:

1–2 seconds per window.

Overlap:

To be determined experimentally.

## Hardware

MPU6050:
- Accelerometer range: To be determined
- Gyroscope range: To be determined

INMP441:
- Sampling rate: To be determined

These values will be finalized after hardware testing.
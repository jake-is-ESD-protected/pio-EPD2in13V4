# PlatformIO compatible [WaveShare](https://www.waveshare.com/) EPD2in13-V4 driver
This code is directly taken from this freely available download link: https://files.waveshare.com/upload/5/50/E-Paper_ESP32_Driver_Board_Code.7z . The code in this configuration works with most ESP32 controllers when used with the Arduino framework. While the [official repo](https://github.com/waveshareteam/e-Paper) has similar code available, the exact configuration in the `.7z` file is not matched, which leads me to host their downloadable version as a PlatformIO compatible repo.

## Disclaimer
Since WaveShare's repo does not have a license, I can not specify a license here. But since their code is freely usable and open, I consider it fair to host a small subset of their driver code here.

## Usage with PlatformIO
Put the following line in your `platformio.ini`:
```ini
...
[your-env]
...
lib_deps = https://github.com/jake-is-ESD-protected/pio-EPD2in13V4
```

# Thermal Imaging Camera with Arduino !
A compact thermal imaging system using a Lepton thermal sensor and ST7796S display. This project captures thermal data and renders it in real-time with multiple color palettes on an embedded display.

# Features :
- Real-time thermal imaging with Lepton 80x60 sensor

- Multiple color palettes (Rainbow HC, Iron Bow, White Hot, Black Hot, and more)

- 2x upscaling to 160x120 resolution for better visibility

- Automatic gain control for optimal image quality

- SPI communication with efficient frame synchronization

# Hardware Components :
- Lepton Thermal Imaging Module

- ST7796S TFT Display

- Arduino-compatible microcontroller

- SPI interface components

# Technical Details :
- Processes 164-byte VOSPI frames

- Implements efficient frame synchronization (SYNC)

- Automatic contrast adjustment based on min/max temperature values

- Supports multiple colormaps for different visualization preferences

Perfect for thermal imaging applications, temperature monitoring, and embedded vision projects.


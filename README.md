# PlantSensor
# Download Drivers # 
ESP32 - https://www.silabs.com/software-and-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads

#Install in Aurdino Library #
- esp32 by Espressif Systems
- TFT_eSPI by Bodmer

# In documents #
- Change Documents → Arduino → libraries → TFT_eSPI → User_Setup_Select.h to
// ===== USER SETUP FOR ESP32 + ST7789 (1.69" 240x280) =====

#define ST7789_DRIVER

#define TFT_WIDTH  240
#define TFT_HEIGHT 280

// ESP32 SPI Pins
#define TFT_MOSI 23
#define TFT_SCLK 18
#define TFT_CS   5
#define TFT_DC   2
#define TFT_RST  4

// Optional (not used)
#define TFT_MISO -1

// Fonts
#define LOAD_GLCD
#define LOAD_FONT2
#define LOAD_FONT4
#define LOAD_FONT6
#define LOAD_FONT7
#define LOAD_FONT8
#define LOAD_GFXFF

// SPI speed
#define SPI_FREQUENCY  40000000

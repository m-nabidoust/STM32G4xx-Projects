# STM32G4xx-Projects
STM32G474VET6 - ARM Cortex-M4 MCU 170MHz
This repository contains **example projects and firmware for STM32G4 series MCUs**.  
It is designed to organize and share projects for various Nucleo and custom boards.

# Features
- VDD 1.71V to 3.6V
- Flash Memory 512KB
- SRAM 96KB
- Frequency up to 170MHz
- Clock managment: 4 to 48MHz crystal oscillator - 32KHz oscillator with calibration - Internal 16MHz RC with PLL - Internal 32KHz RC oscillator
- Pins: LQFP 100 14 x 14 x 1.4 mm
  
## Supported Boards & MCUs
- STM32G4VET6_Developement Kit is made by PishgamanIEA Co
- STM32G431, STM32G474, STM32G484, and other STM32G4 series MCUs

## Project Structure
| 🗂️ **Category**        | ⚙️ **Module**                | 💡 **Example Project** | 🧾 **Description**                                      | 💻 **Language** |
| ----------------------- | ---------------------------- | ---------------------- | ------------------------------------------------------- | --------------- |
| 🔌 **GPIOs**            | Input / Output               | `gpio_toggle`          | Basic input/output pin control, LED blink, button input | C               |
| 🧩 **System Core**      | DMA                          | `dma_transfer`         | Memory-to-peripheral data transfer example              | C               |
|                         | IWDG / WWDG                  | `watchdog_demo`        | Independent & window watchdog timer usage               | C               |
|                         | RCC / SYS                    | `system_clock_config`  | Configure system clock, PLL, HSE/HSI                    | C               |
| ⚡ **Analog**            | ADC                          | `adc_multi_channel`    | Multi-channel ADC with DMA                              | C               |
|                         | DAC                          | `dac_wave_gen`         | Generate analog waveforms                               | C               |
|                         | OPAMP                        | `opamp_buffer`         | Internal operational amplifier as voltage follower      | C               |
|                         | COMP                         | `comparator_threshold` | Analog comparator with interrupt output                 | C               |
| ⏱️ **Timers**           | Timer / PWM                  | `pwm_output`           | Generate PWM signals for motor or LED dimming           | C               |
|                         | HRTIM                        | `hrtim_motor_control`  | High-resolution timer for motor drive                   | C               |
|                         | LPTIM                        | `lowpower_timer`       | Low-power timer for periodic wake-up                    | C               |
|                         | RTC                          | `real_time_clock`      | Real-time clock with alarm and backup                   | C               |
| 🔗 **Connectivity**     | I2C                          | `i2c_eeprom`           | Read/write EEPROM via I2C                               | C               |
|                         | SPI                          | `spi_lcd`              | Communicate with display using SPI                      | C               |
|                         | UART / LPUART                | `uart_console`         | Serial communication example                            | C               |
|                         | USB                          | `usb_cdc`              | USB virtual COM port                                    | C               |
|                         | FDCAN                        | `fdcan_loopback`       | CAN bus communication test                              | C               |
|                         | QUADSPI                      | `qspi_flash`           | Read/write external flash memory                        | C               |
| 🎧 **Multimedia**       | I2S / SAI                    | `i2s_audio_codec`      | Audio streaming via I2S                                 | C               |
| 🔒 **Security**         | RNG                          | `rng_demo`             | Random number generator example                         | C               |
| 🧮 **Computing**        | CORDIC                       | `cordic_trig`          | Fast trigonometric calculations using CORDIC            | C               |
|                         | CRC                          | `crc_check`            | Data integrity verification                             | C               |
|                         | FMAC                         | `fmac_filter`          | Digital filtering using hardware FMAC unit              | C               |
| 🖥️ **Displays**        | TFT / OLED / LCD / 7-Segment | `oled_display`         | Show text and sensor data                               | C               |
| 📡 **Modules**          | Wi-Fi / Bluetooth / GPS      | `wifi_mqtt`            | IoT connectivity example                                | C               |
| 🌡️ **Sensors**         | Temperature / Accelerometer  | `sensor_read`          | Read data via I2C/SPI                                   | C               |
| ⌨️ **Keyboard / Input** | Keypad / Touch               | `keypad_scan`          | Matrix keypad scanning and debouncing                   | C               |


## Library MCU
- Bare-Metal
- LL and HAL
- FreeRTOS

## Compilers and Software 
- STM32CubeMX
- STM32CubeIDE
- Keil
- STM32CubePROG
- Visual Studio Code
- Altium Designer
- Proteus
## Link and website
🔗 Linkedin <div class="badge-base LI-profile-badge" data-locale="en_US" data-size="medium" data-theme="dark" data-type="VERTICAL" data-vanity="mohammad-nabidoust-660150283" data-version="v1"><a class="badge-base__link LI-simple-link" href="https://ir.linkedin.com/in/mohammad-nabidoust-660150283?trk=profile-badge">Mohammad Nabidoust</a></div>
              

# STM32 Firmware Lab

Progressive embedded firmware exercises demonstrating core skills on STM32 microcontrollers. Each exercise builds on the previous one, moving from bare-metal basics through RTOS, communication protocols, and design patterns.

## Hardware

- **STM32 B-L475E-IOT01A** — Cortex-M4, IoT Discovery Kit (WiFi, BLE, sensors)
- **STM32F469 Discovery** — Cortex-M4, LCD display, rich peripherals

## Exercises

| # | Topic | Peripherals | Status |
|---|-------|-------------|--------|
| 01 | GPIO Blink | GPIO | Planned |
| 02 | UART Debug Output | UART, printf redirect | Planned |
| 03 | ADC Reading | ADC, UART | Planned |
| 04 | Timer / PWM | TIM, PWM | Planned |
| 05 | I2C Sensor | I2C, HTS221 (temperature/humidity) | Planned |
| 06 | SPI Sensor | SPI, LPS22HB (pressure) | Planned |
| 07 | Watchdog Timer | IWDG | Planned |
| 08 | FreeRTOS Tasks | FreeRTOS, GPIO | Planned |
| 09 | FreeRTOS Queues | FreeRTOS, ADC, UART | Planned |
| 10 | FreeRTOS Semaphores | FreeRTOS, mutex, UART | Planned |

*Status will be updated as exercises are completed.*

## Repository Structure

```
stm32-firmware-lab/
├── exercises/
│   ├── 01_gpio_blink/
│   ├── 02_uart_debug/
│   ├── 03_adc_reading/
│   └── ...
└── README.md
```

Each exercise folder contains its own STM32CubeIDE project and a brief README explaining the objective, wiring (if needed), and key learnings.

## Tools

- **IDE:** STM32CubeIDE
- **Debugger:** ST-Link (on-board)
- **Language:** C

## Author

**Luca Agrippino** — Embedded Software Engineer
[LinkedIn](https://www.linkedin.com/in/luca-agrippino) · [GitHub](https://github.com/LucaAgrippino)

# Exercise 01 — GPIO Blink

## Objective
Toggle an on-board LED at a fixed interval using GPIO output and HAL delay.

## Board
STM32 B-L475E-IOT01A

## Pin Configuration
| Pin  | Function    | Description     |
|------|-------------|-----------------|
| PB14 | GPIO_Output | LED2 (green)    |

## Key Learnings
- STM32CubeIDE project creation and .ioc configuration
- HAL GPIO functions: HAL_GPIO_TogglePin()
- HAL_Delay() for simple timing

## Build & Flash
1. Open project in STM32CubeIDE
2. Build (Ctrl+B)
3. Flash and run (F11 or Run → Debug)
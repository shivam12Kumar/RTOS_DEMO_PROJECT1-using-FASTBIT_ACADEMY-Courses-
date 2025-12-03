# RTOS_DEMO_PROJECT1-using-FASTBIT_ACADEMY-Courses-
This application takes commands as input over UART and handles LED as well as RCT peripherl's of MCU

This Application implements - 
1. Processing user sent command over UART
2. FreeRTOS queues handling
3. FreeRTOS Software Timers

# we will use MINICOM serial terminal in our linux platform to get commands from user . 
# we are using STM32F407G-DISCO Board By ST microelectronics .
# We will use a USB to TTL converted b/w our board and host PC as we dont have Virtual COM support in our board.

## We are using CUBE IDE by ST and we will import our intial code by generating it using CUBE MX .
## We will add FreeRTOS library manually and not generate it with CUBE MX.
## We will use FreeRTOS-Kernel"  version: "v11.1.0"  and CUBE IDE 2.0.0 (latest version's of both as of today)

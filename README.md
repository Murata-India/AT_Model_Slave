Modem firmware for the at slave based on STM32 cube SDK. Default firmware is tweaked to support AT command transmssion from UART1 (LPUART in the original firmware) UART TX Enable bit of CR1 register is disbaled before entering the stop mode and enabled back again to reduce power consumption.


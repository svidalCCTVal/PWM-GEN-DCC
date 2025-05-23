# PWM-GEN-DCC
Proyecto de prueba para placa DCC. La idea es que pueda recibir comandos por UART para variar la frecuencia de operación de 1MHz a 3.5MHz. 

## Respecto al proyecto
- Este proyecto se realizó basado en la placa de desarrollo Nucleo 64 STM32F401RET6, utilizando los timers y comparadores de cada uno.

![IOC PWM GEN DCC](https://github.com/user-attachments/assets/3666391f-e41f-480f-89c3-afdea8479b85)

- En main.c se encuentra la forma de generar los PWM por comparadores con los registro CRRx de cada canal en cada timer.

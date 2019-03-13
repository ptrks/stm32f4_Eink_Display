# stm32f4_Eink_Display
Starter project for using the Waveshare 1.54 Inch E-Ink display with a STM32F4 

---

### About
This project can be used as a starting point to getting the 1.54inch Waveshare up and running on a stm32 based board. The code will make use of standard SPI periphials on the evaluation baord to communicate with the display. Another example is in the works that will demonstrate using DMA to communicate directly to the SPI periphial.

--- 
### Hardware Used
* [STM32F469I Discovery Evaluation Board by ST](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mcu-mpu-eval-tools/stm32-mcu-mpu-eval-tools/stm32-discovery-kits/32f469idiscovery.html)
* [200x200 1.54inch E-Ink Display by Waveshare](https://www.waveshare.com/1.54inch-e-Paper-Module-B.htm)

---
### Getting Started

#### Prequisites 
To sucessfully build and flash this project you will need the following:
* [stllink - will be used to flash the stm32f4 development board](https://github.com/texane/stlink)
* [The most up to date standard periphial library provided by ST](https://www.st.com/en/embedded-software/stsw-stm32065.html)

#### Testing
TBD

#### Build and Flash

```make && make flash```

----

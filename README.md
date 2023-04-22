# ReaderPen KiCAD

KiCAD files for Reader Pen project. Manufacturing files for the PCB can be found here: https://github.com/sanrav2016/ReaderPenPCB.

Image of the schematic:
![image](https://user-images.githubusercontent.com/88633866/233760096-b721fdd6-cfee-4fd1-beea-1d02b517f824.png)

Some notes:
- We are using the STM32H723 microcontroller. STM is a reputable microcontroller manufacturer that dominates the commercial embedded systems market. This particular model belongs to their high-performance MCU series. The STM32H723 has a Cortex M7, and the VET6 can run at 550MHz with 1 M flash and 564 K RAM. We have included an external 50 MHz clock. 
- We are using the TP4056 for microUSB charge control for a 3.7V 1000mAh LiPo battery.
- RGB LED for status indication
- Scan LEDs to highlight paper when reading
- The camera module in this system is the Himax HM01B0. It will not be ordered as we already have it at home from the Arducam module. A 2.8V LDO is necessarily included. 
- SWD for programming
- TRRS audio jack for speaker and mic (ADC/DAC). For simplicity no DSP is implemented.

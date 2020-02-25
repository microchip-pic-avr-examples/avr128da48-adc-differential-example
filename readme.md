<img src="images/microchiptechnologyinc.png" height="60" >

# AVR128DA48 ADC Differential Example

## Objective:
The AVR128DA48 features one 12-bit differential ADC. In this demo, one POT click board and one POT 2 click board will be attached to the mikroBus socket #1 and socket #2 of a Curiosity Nano Base board and the analog values provided by the two potentiometers will be read using AIN3 and AIN4 channels.

## Demo Configuration:
The AVR128DA48 Curiosity Nano Development Board (DM164151) is used as the test platform. The following configurations must be made for this project:
- PD3 pin - Configured as analog input (AIN3)
- PD4 pin - Configured as analog input (AIN4)
- ADC0 - Configured in Free Run Mode and with Differential mode activated
- VREF - Reference voltage for ADC0 set to 2.048V

### AVR128DA48 Curiosity Nano with POT click
<img src="images/ADC_differential_setup.png" height="500" >

## Required Tools
- Atmel Studio 7.0.2397 or newer
- AVR-Dx 1.0.18 or newer Device Pack
- AVR128DA48 Curiosity Nano (DM164151)
- Curiosity Nano Base (AC164162)
- MikroelEktronika POT click (MIKROE-3402)
- MikroelEktronika POT 2 click (MIKROE-3325)

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.

## Conclusion:
The demo provides an example of differential ADC application. Please refer to the AVR128DA48 datasheet for more information or specifications.

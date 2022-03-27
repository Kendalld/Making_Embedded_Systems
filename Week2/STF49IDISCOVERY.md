32F429IDISCOVERY Discovery kit with STM32F429ZI MCU

MPN: STM32F429I-DISC1
Digikey PN: 497-16140-ND
32F429IDISCOVERY

[Product Brief](https://www.st.com/content/ccc/resource/technical/document/data_brief/ff/c1/b6/02/c3/b4/49/cb/DM00094498.pdf/files/DM00094498.pdf/jcr:content/translations/en.DM00094498.pdf)
[User Manual](https://www.st.com/content/ccc/resource/technical/document/user_manual/6b/25/05/23/a9/45/4d/6a/DM00093903.pdf/files/DM00093903.pdf/jcr:content/translations/en.DM00093903.pdf)
[Software Manual](https://www.st.com/resource/en/user_manual/dm00097320-getting-started-with-stm32f429-discovery-software-development-tools-stmicroelectronics.pdf)

## What kind of processor is it?
STM32F429ZIT6

>"High-performance advanced line, Arm Cortex-M4 core with DSP and FPU, 2 Mbytes of Flash memory, 180 MHz CPU, ART Accelerator, Chrom-ARTAccelerator, FMC with SDRAM, TFT"

[datasheet](https://www.st.com/resource/en/datasheet/stm32f429ng.pdf)

## How much Flash and RAM does it have? Any other memory types?
Flash: 2 Mbytes
RAM: 256 Kbytes

SDRAM: 64 Mbit
## Does it have any special peripherals? (List 3-5 that you find interesting.)

![STM32F429ZI_UM1670_Rev5_Fig2_Block_Diagram]()

1. 2.4" QVGA TFT LCD
    QVGA: Quarter VGA display with 320 × 240 resolution
    [TFT](https://en.wikipedia.org/wiki/Thin-film-transistor_liquid-crystal_display): Thin-film-transistor - Manufacturing process with thin film of silicon on glass
2. I3G4250D
    ST MEMS motion sensor 3-axis digital output gyroscope

3. ST-LINK/V2-B Debugger
    Programmer
    Easier to debug/step through code. 

## If it has an ADC, what are the features?
Brief Summary:
>"3×12-bit, 2.4 MSPS ADC: up to 24 channels and 7.2 MSPS in triple interleaved mode"
Data Sheet Summary
>"Three 12-bit analog-to-digital converters are embedded and each ADC shares up to 16
>external channels, performing conversions in the single-shot or scan mode. In scan mode,
>automatic conversion is performed on a selected group of analog inputs.
>Additional logic functions embedded in the ADC interface allow:
>• Simultaneous sample and hold
>• Interleaved sample and hold
>The ADC can be served by the DMA controller. An analog watchdog feature allows very
>precise monitoring of the converted voltage of one, some or all selected channels. **An
>interrupt is generated when the converted voltage is outside the programmed thresholds.**
>To synchronize A/D conversion and timers, the ADCs could be triggered by any of TIM1,
>TIM2, TIM3, TIM4, TIM5, or TIM8 timer"
stm32f29ng pg 43

Cool interrupt triggering. Could be useful for sensor saftey features 


TIM = Timer
TIM6 and 7 aren't used because they aren't General-purpose and deal with DAC or DMA stuff

## How much does the board cost vs what the processor costs? Is the processor in stock anywhere? (Try Digikey, Mouser, Octopart, Google, and so on.)

MCU:
    [Purchasing](https://octopart.com/search?autosugg_idx=0&currency=USD&oq=STM32F429ZIT6&q=STM32F429ZIT6&specs=1)
    In Stock(3/27/2020): QTY 0
    EA @ MOQ 1: $20.6

Dev Board:
    [Purchasing](https://octopart.com/search?q=STM32F429I-DISC1&currency=USD&specs=0)
    In Stock(3/27/2020): QTY 100+
    EA @ MOQ 1: $29.9
    


## Look at one application note for this board.

User Manual states software examples at: http://www.st.com/stm32f4-discovery
Actually found: https://www.st.com/en/evaluation-tools/stm32-discovery-kits.html#documentation -> Application Note

[SPI protocol used in the STM32 bootloader](https://www.st.com/resource/en/application_note/an4286-spi-protocol-used-in-the-stm32-bootloader-stmicroelectronics.pdf)


## More resources:

[STM32 Cortex -M4 Programming Manual](https://www.st.com/resource/en/programming_manual/pm0214-stm32-cortexm4-mcus-and-mpus-programming-manual-stmicroelectronics.pdf)


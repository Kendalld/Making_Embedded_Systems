
# The MIKROE-3521

[MIKROE mcu card product flyer](https://download.mikroe.com/flyers/mcu-card-flyer-web.pdf)
[MCU Card 6 for STM32 Schematic](https://download.mikroe.com/examples/full-featured-boards/8th-generation/schematic/schematic-mcu-card-6-for-stm32.pdf)

The MIKROE-3521 is a swappable MCU module/daughter card intendend for seating and use in a much larger Motherboard/Dev Kit.
There are little active components on the board, but large male and female mezzanine connectors.

## What kind of processor is it?
[STM32L081CB](https://www.st.com/en/microcontrollers-microprocessors/stm32l081cb.html)
    "Ultra-low-power ARM Cortex-M0+ MCU with 128-Kbytes Flash, 32 MHz CPU, AES"

## How much Flash and RAM does it have? Any other memory types?
Flash: 128000 bytes
RAM:    20480 bytes
No other types of memory

## Does it have any special peripherals? (List 3-5 that you find interesting.)
This board does not really have peripherals, but it is interesing:
- The enormous pin count on the mezzinene connectors try and future proof the posibility of a high pin MCU not being pin compatible with the fancy dev kit.
- The silk screen pairs the MCU pin name to it's functions to the dev board. 
    - In this case there are 4 "Microbuses" that take 12 pins each and are repeating.
    - This is done, presumably, to ensure varying MCU module compatability to the mother board by simply repeating the pattern.
        - Update: I was wrong, there microbus connectors on the motherboard for plug and play periferal hats also sold at mikroe
    - I don't know enough to say if this is set in stone, but it feels like this would severly limit the versatility of higher pin count MCUs. 

## If it has an ADC, what are the features?

N/A

## How much does the board cost vs what the processor costs? Is the processor in stock
anywhere? (Try Digikey, Mouser, Octopart, Google, and so on.)
    ### Board: MIKROE-3521
    [Purchasing](https://www.digikey.com/en/products/detail/mikroelektronika/MIKROE-3521/10186996)
         EA: $35.00 
         In Stock(3/26/2022): 
            Digikey: QTY 3 
            Newark: QTY 10
            Farnell: QTY 10
         Lead Time: 4weeks
     [Maunfacturer Website](https://www.mikroe.com/mcu-card-6-for-stm32-stm32l081cb)

    ### Processor: STM32L081CB
    [datasheet](https://www.st.com/content/ccc/resource/technical/document/datasheet/ab/81/9e/a3/49/a9/46/be/DM00162467.pdf/files/DM00162467.pdf/jcr:content/translations/en.DM00162467.pdf)
    [Purchasing](https://www.digikey.com/en/products/detail/stmicroelectronics/STM32L081CBT6TR/8257887)
        EA: $3.65
        In stock(3/26/2022): QTY 0 
        Lead Time: 45weeks
    [Maunfacturer Website](https://www.st.com/en/microcontrollers-microprocessors/stm32l081cb.html)

    ### Motherboard : Fusion for STM32 v8
    [Product Page](https://www.mikroe.com/fusion-for-stm32)
        EA: 
            Board: $300.00
            Wifi Programming license: $100
            Wifi SSL security license: $100


## Look at one application note for this board.

This looks like a premium ecosystem mostly for proof of conecpt and education. 
The MCU can be changed easily to do preferal benchmarking on the exact same hardware setup.
The motherboard has a billion dip switches and buttons that look incredibly cool, but seem a far cry from narrowing in on how a product would look and behave.

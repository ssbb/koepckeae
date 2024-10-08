# koepckeae

![PCB](./images/assembled.jpg)

koepckeae is a 34-key unibody split keyboard higihly inspired by Pete Johanson's [Zaphod Lite](https://gitlab.com/lpgalaxy/zaphod/-/tree/main), featuring hotswap support, splay, and spaced out thumbs.

## BOM

| Qty | Name                                                        | Source                                                                                                             |
|-----|-------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| 1   | PCB                                                         | [gerbers](pcb/choc/koepckeae_gerbers.zip)                                                                          |
| 1   | XIAO nRF52840                                               | [Digikey](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/102010448/16652893)                   |
| 1   | 74HC595D shift register (SOIC-16)                           | [LCSC](https://www.lcsc.com/product-detail/Shifting-Register_Nexperia-74HC595D-118_C5947.html)                     |
| 1   | PCM12 power switch                                          | [LCSC](https://www.lcsc.com/product-detail/Slide-Switches_C-K-PCM12SMTR_C221841.html)                              |
| 1   | Panasonic EVQPUC02K reset button                            | [LCSC](https://www.lcsc.com/product-detail/_PANASONIC-_C79174.html)                                                |
| 2   | 1x1 Mill-Max Spring Loaded Header (0906-2-15-20-75-14-11-0) | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/0906-2-15-20-75-14-11-0/1147050)  |
| 2   | 1x7 Mill-Max Header (310-43-107-41-001000)                  | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/310-43-107-41-001000/1212181)     |
| 1   | JST PH-2.0 battery socket                                   | [LCSC](https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-S2B-PH-K-S-LF-SN_C173752.html) |
| 1   | 702025 300 mAh battery                                      |                                                                                                                    |
| 34  | 1N4148W diode                                               | [LCSC](https://www.lcsc.com/product-detail/Switching-Diode_MDD-Microdiode-Electronics-1N4148W_C84367.html)         |
| 34  | Kailh Choc hotswap sockets                                  | [Aliexpress](https://aliexpress.com/item/33023283633.html?sku_id=10000000883911874)                                |

Max battery dimensions are 29mm x 21mm x 8mm. Ideally get a battery with JST connector but double check polarity on PCB.

### Plate case

| Qty | Name         | Source                                                             |
|-----|--------------|--------------------------------------------------------------------|
| 1   | Bottom Plate | [gerbers](mechanical/bottom-plate/bottom_plate_gerbers.zip)        |
| 8   | Solder Nuts  | [LCSC](https://www.lcsc.com/product-detail/_Sinhoo-_C2916384.html) |
| 8   | M2x5 screws  |                                                                    |

### Display

| Qty | Name                                                     | Source                                                                                                         |
|-----|----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| 1   | Adafruit Sharp Memory Display                            | [Adafruit](https://www.adafruit.com/product/3502)                                                              |
| 1   | 1x5 Mill-Max Spring Loaded Header (825-22-005-10-001101) | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/825-22-005-10-001101/6149696) |
| 4   | M2.5x6 male-female nylon standoff                        | [Aliexpress](https://aliexpress.com/item/32871403400.html?sku_id=10000002420611426)                            |
| 4   | M2.5 nylon nut                                           | [Aliexpress](https://aliexpress.com/item/32868992270.html?sku_id=10000010058105677)                            |
| 4   | M2.5x6 nylon screw                                       | [Aliexpress](https://aliexpress.com/item/32870030598.html?sku_id=10000002668418327)                            |

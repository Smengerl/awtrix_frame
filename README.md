# Ultra-low-cost AWTRIX build

AWTRIX is an awesome and very flexible visualization companion for smart home and other application.
It was initially designed to be flashed to the Ulanzi pixel clock, which currently comes at a price of 50 USD, but it also supports custom builds.
I wanted a full featured custom build with professional look but at a much lower pricepoint than the original, but didn't find a good howto - so I created this one.

Full source code for AWTRIX available here: [AWTRIX repo](https://github.com/Blueforcer/awtrix3) 

Features:
- Base build is under 20 USD, full feature set about 25USD
- 32*8px display with light-diffusor for pixel look
- Clean "fullblack" effect when off  
- Three menu buttons
- Stylable by easily exchangeable covers with different colors and touch
- Preparation for wall hanging mount
- and stand supports
- Optional light sensor 
- Optional DF Player MP3 sound
- Optional buzzer


Note that I didn't foresee support for the battery and the battery sensor as I don't think this is a beneficial feature due to the high power demands of the display. 

Also the temperature/humidity sensor I did not include in the housing as the heat dissipation from the display will hinder any accurate reading when using a sensor in the same housing. Alternartively use a regular separate weather station sensor and display its reading to the AWTRIX screen.


# Index
- [Buy parts](#buy-parts)
- [Printing and assembly](#printing-and-assembly)
- [Customization ideas](#customization-ideas)
- [Acknowledgements](#Acknowledgements)


| Left iso | top | right iso | back |
| -------- | --- | --------- | ---- |
| <img src="./instructions/rendering/left.png" width=300px /> | <img src="./instructions/rendering/top.png" width=300px /> | <img src="./instructions/rendering/right.png" width=300px /> | <img src="./instructions/rendering/back.png" width=300px /> |



## Buy parts

Mandatory parts:

| Unit price | Quantity | Partname | Example | Notes |
| ---------- | -------- | -------- | ------- | ----- |
| 5 USD      | 1        | ESP32 Dev Module | <a href="https://de.aliexpress.com/item/1005006124752051.html">AliExpress</a> | Case designed for WROVER USB-C type. Other types also fit but might be glued |
| 8 USD      | 1        | WS2812B matrix 8x32 | <a href="https://de.aliexpress.com/item/4001296811800.html">AliExpress</a> |  |
| 1 USD      | 1        | 4 pushbutton element | <a href="https://de.aliexpress.com/item/1005007177677170.html">AliExpress</a> | When using the 4 buttons element, connect the outputs for the two middle buttons to "or" their signal. Unsolder the LED to get cleaner look |
| 2 USD      | 1        | semi-transparent acrylic board | <a href="https://de.aliexpress.com/item/32857098929.html">AliExpress</a> | Optional, for cleaner look. Best when using semi-transparent black acryl. 2mm thickness hold tight in case. Thinner sheets need to be glued to base. Peace of at least 338*98mm required.  |
| <1 USD     | 25       | Flathead screws M2,5 or M3. 6mm. e.g. DIN 7984 | <a href="https://de.aliexpress.com/item/1005006166060947.html">AliExpress</a> | Use low head version if possible for best look ("laptop screws") |

Optional parts:

| Unit price | Quantity | Partname | Example | Notes |
| ---------- | -------- | -------- | ------- | ----- |
| 1 USD      | 1        | DF Player mini | <a href="https://de.aliexpress.com/item/1005006263283726.html">AliExpress</a> | Optional, for MP3 playback |
| 1 USD      | 1        | Loudspeaker 8 Ohm | <a href="https://de.aliexpress.com/item/1005006358049156.html">AliExpress</a> | Optional, for MP3 playback. Watch for dimensions |
| <1 USD     | 1        | Buzzer | <a href="https://de.aliexpress.com/item/1005004883467830.html">AliExpress</a> | Optional, for signaling |
| <1 USD     | 1        | LDR GL5516 | <a href="https://de.aliexpress.com/item/1005005693826904.html">AliExpress</a> | Optional, for auto brightness |



## Printing and assembly

The printing and assembly process consist of 5 steps:
- [Step 1: Diffusor](./instructions/step_1.md)
- [Step 2: Base](./instructions/step_2.md)
- [Step 3: Pushbuttons](./instructions/step_3.md)
- [Step 4: Covers](./instructions/step_4.md)
- [Step 5: Anti-slip pads](./instructions/step_5.md)

Remarks on printer settings:
- All printed parts designed for PETG besides for the anti-slip pads (TPU) or the diffusor (worked best on PLA). 
- Best experience on my printer was to print the part in the direction as shown in the thumbnails
- no supports needed unless explicitely noted
- Using fuzzy skin for all outside walls creates a nice look
- No rafts/brim etc. reguired for any model.



## Customization ideas

The housing offers some mechanical customzation options:
- add all the optional features such as the buzzer
- print covers in different colors and use different colors for pushbutton and cover
- use fuzzy skin or other effects for cover



## Acknowledgements
- Blueforcer for launching awesome AWTRIX3 project 


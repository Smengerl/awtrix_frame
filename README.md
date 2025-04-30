# Ultra-low-cost AWTRIX frame 

Housing to build an AWTRIX pixel clock at very low price point (<20 USD)
- 32*8px display "fullblack" with light-diffusor 
- Three buttons to navigate menu
- Optional light sensor
- Optional DF Player sound 
- Optional buzzer


# Index
- [Mechanics](#Mechanics)
- [Electronics](#Electronics)
- [Software](#Software)
- [Usage](#Usage)
- [Customization ideas](#customization_ideas)
- [Acknowledgements](#Acknowledgements)



## Mechanics

Printer settings:
- All printed parts designed for PETG. 
- Best experience on my printer was to print the part in the direction as shown in the thumbnails
- unless explicitely noted no supports needed
- Using fuzzy skin for all outside walls creates a nice look
- No rafts/brim etc. reguired for any model.






### Step 1: Diffusor

#### 3D-Printed Parts

| Filename                           | Thumbnail                                              | Required | Notes |
| ---------------------------------- | -------------------------------------------------------| -------- | ------|
| `./print/diffusor/diffusor.stl`    | <img src="./print/diffusor/rendering/diffusor.png"/>   | 2        | Standard white PLA gave best diffusor effect |
| `./print/diffusor/grid_middle.stl` |<img src="./print/diffusor/rendering/grid_middle.png"/> | 2        | Use full black PETG for best stability and contrast |
| `./print/diffusor/grid_side.stl`   |<img src="./print/diffusor/rendering/grid_side.png"/>   | 4        | Use full black PETG for best stability and contrast |

#### Assembly

- Snap in the grids to the diffusor from both directions
- Use the larger "middle grid" to tie both diffusor part together as shown in assembly animation
- One outside wall of the "diffusor_side" is a little thinner than the other wall. Use this to face to the middle grid to achieve best look  
- make sure the upper grid is fully pressed in so that surface of diffusor and grid is fully leveled, this may require some force

![assembly](./print/diffusor/rendering/assembly.gif)







### Step 2: Base

#### 3D-Printed Parts

Note: no part of the base will be visible any longer once the cover is attached, so you can use up leftover filament

| Filename                            | Thumbnail                                                | Required | Notes |
| ----------------------------------- | ---------------------------------------------------------| -------- | ------|
| `./print/base/base_left.stl`        | <img src="./print/base/rendering/base_left.png"/>        | 1        | Invisible in assembled state |
| `./print/base/base_right.stl`       | <img src="./print/base/rendering/base_left.png"/>        | 1        | Invisible in assembled state |
| `./print/base/base_middle.stl`      | <img src="./print/base/rendering/base_middle.png"/>      | 1        | Invisible in assembled state |
| `./print/base/base_lower_left.stl`  | <img src="./print/base/rendering/base_lower_left.png"/>  | 1        | Invisible in assembled state |
| `./print/base/base_lower_right.stl` | <img src="./print/base/rendering/base_lower_right.png"/> | 1        | Invisible in assembled state |


#### Standard parts

| Unit price | Quantity | Partname | Example | Notes |
| ---------- | -------- | -------- | ------- | ----- |
| 5 USD      | 1        | ESP32 Dev Module | <a href="https://de.aliexpress.com/item/1005006124752051.html">AliExpress</a> | Case designed for WROVER USB-C type. Other types also fit but might be glued |
| 8 USD      | 1        | WS2812B matrix 8x32 | <a href="https://de.aliexpress.com/item/4001296811800.html">AliExpress</a> |  |
| 1 USD      | 1        | DF Player mini | <a href="https://de.aliexpress.com/item/1005006263283726.html">AliExpress</a> | Optional, for MP3 playback |
| 1 USD      | 1        | Loudspeaker 8 Ohm | <a href="https://de.aliexpress.com/item/1005006358049156.html">AliExpress</a> | Optional, for MP3 playback. Watch for dimensions |
| <1 USD     | 1        | Buzzer | <a href="https://de.aliexpress.com/item/1005004883467830.html">AliExpress</a> | Optional, for signaling |
| <1 USD     | 1        | LDR GL5516 | <a href="https://de.aliexpress.com/item/1005005693826904.html">AliExpress</a> | Optional, for auto brightness |
| <1 USD     | 14       | Flathead screws M2,5 or M3. >=6mm. e.g. DIN 7984  | <a href="https://de.aliexpress.com/item/1005006166060947.html">AliExpress</a> | Use low head version if possible for best look ("laptop screws") |








### Step 3: Pushbuttons

#### 3D-Printed Parts

| Filename                                    | Thumbnail                                                        | Required | Notes |
| ------------------------------------------- | -----------------------------------------------------------------| -------- | ------|
| `./print/pushbutton/pushbutton_base.stl`    | <img src="./print/pushbutton/rendering/pushbutton_base.png"/>    | 1        | Invisible in assembled state |
| `./print/pushbutton/pushbutton_clicker.stl` | <img src="./print/pushbutton/rendering/pushbutton_clicker.png"/> | 1        | Make sure to print in the depicted direction and enable light supports |


#### Standard parts

| Unit price | Quantity | Partname | Example | Notes |
| ---------- | -------- | -------- | ------- | ----- |
| 1 USD      | 1        | 4 pushbutton element | <a href="https://de.aliexpress.com/item/1005007177677170.html">AliExpress</a> |  |
| <1 USD     | 4        | Flathead screws M2,5 or M3. >=6mm. e.g. DIN 7984  | <a href="https://de.aliexpress.com/item/1005006166060947.html">AliExpress</a> | Use low head version if possible for best look ("laptop screws") |









### Step 4: Covers

#### 3D-Printed Parts

Notes:
- Consider fuzzy skin for outside walls
- Use a nice color to personalize your AWTRIX
- Priting in depicted direction requires supports only at the location of the pushbuttons (consider disable auto supports and use paint-on supports at these locations)

| Filename                        | Thumbnail                                            | Required | Notes |
| ------------------------------- | -----------------------------------------------------| -------- | ------|
| `./print/cover/cover_left.stl`  | <img src="./print/cover/rendering/cover_left.png"/>  | 1        |       |
| `./print/cover/cover_right.stl` | <img src="./print/cover/rendering/cover_right.png"/> | 1        |       |

#### Standard parts

| Unit price | Quantity | Partname | Example | Notes |
| ---------- | -------- | -------- | ------- | ----- |
| <1 USD     | 7        | Flathead screws M2,5 or M3. >=6mm. e.g. DIN 7984  | <a href="https://de.aliexpress.com/item/1005006166060947.html">AliExpress</a> | Use low head version if possible for best look ("laptop screws") |
| 2 USD      | 1        | semi-transparent acrylic board | <a href="https://de.aliexpress.com/item/32857098929.html">AliExpress</a>  | max 2mm thick, peace of at least 338*98mm. Optional, for cleaner look. Best when using semi-transparent black acryl |

#### Assembly

Cut the acrylic board as shown:
![assembly](./print/cover/rendering/acryl.png)



### Step 5: Anti-slip pads
Optionally you might want to add TPU [anti-slip pads](./print/antislip/antislip.stl) to the AWTRIX which gives it a solid stand in laying (8 pads) and/or upright position (3 pads).
Assemble these pads at the indicated locations on the base and cover via double sided tape. 

Alternatively you can use standard non-slip pads or even cut peaces of standard rubber pads and attach them with double sided tape.

Location of the pads for upright position:
<img src="./print/antislip/rendering/antislip_upright.png"/>

Location of the pads for laying or wall hanging position:
<img src="./print/antislip/rendering/antislip_back.png"/>





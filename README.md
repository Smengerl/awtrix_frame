# Ultra-low-cost AWTRIX frame 

Housing to build an AWTRIX pixel clock at very low price point (<20 USD)
- 32*8px display "fullblack" with light-diffusor 
- Three buttons to navigate menu
- Optional light sensor
- Optional TF Player sound 
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


### Step 3: Pushbuttons

#### 3D-Printed Parts

| Filename                                    | Thumbnail                                                        | Required | Notes |
| ------------------------------------------- | -----------------------------------------------------------------| -------- | ------|
| `./print/pushbutton/pushbutton_base.stl`    | <img src="./print/pushbutton/rendering/pushbutton_base.png"/>    | 1        | Invisible in assembled state |
| `./print/pushbutton/pushbutton_clicker.stl` | <img src="./print/pushbutton/rendering/pushbutton_clicker.png"/> | 1        | Make sure to print in the depicted direction and enable light supports |



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

| Name              | Spec                          | Required | Notes |
| ----------------- | ----------------------------- | -------- | ------|
| countersunk screw | M3 6mm, e.g. DIN 7984         | 7        | Use low head version if possible for best look ("laptop screws") |
| semi-transparent acrylic board | max 2mm          | 1        | Optional, for cleaner look |

#### Assembly

Cut the acrylic board as shown:
![assembly](./print/cover/rendering/acryl.png)



### Step 5: Anti-slip pads
Optionally you might want to add TPU [anti-slip pads](./print/antislip/antislip.stl) to the AWTRIX which gives it a solid stand in laying (8 pads) and/or upright position (3 pads).
Assemble these pads at the indicated locations on the base and cover. 
Alternatively you can use standard rubber pads and attach them with double sided tape.

Location of the pads for upright position:
<img src="./print/antislip/rendering/antislip_upright.png"/>

Location of the pads for laying or wall hanging position:
<img src="./print/antislip/rendering/antislip_back.png"/>



#### Standard parts

| Name              | Spec                          | Required | Notes |
| ----------------- | ----------------------------- | -------- | ------|
| countersunk screw | M3 5mm, e.g. DIN EN ISO 4762  | 4        | To attach ESP to back of housing |
| countersunk screw | M3 5mm, e.g. DIN EN ISO 4762  | 4        | To attach display to back of housing |
| cylinder head screw | M3 10mm | 4        | To fix back and front of housing |
| semi-transparent acrylic board | max 2mm, 95-100mm * 40-50mm | 1        | Optional, for cleaner look |



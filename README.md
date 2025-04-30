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


### Step 3: Pushbuttons


### Step 4: Covers

#### Standard parts

| Name              | Spec                          | Required | Notes |
| ----------------- | ----------------------------- | -------- | ------|
| countersunk screw | M3 5mm, e.g. DIN EN ISO 4762  | 4        | To attach ESP to back of housing |
| countersunk screw | M3 5mm, e.g. DIN EN ISO 4762  | 4        | To attach display to back of housing |
| cylinder head screw | M3 10mm | 4        | To fix back and front of housing |
| semi-transparent acrylic board | max 2mm, 95-100mm * 40-50mm | 1        | Optional, for cleaner look |



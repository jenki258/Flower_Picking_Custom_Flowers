## **Double flower Configuration Description**  

## **Basic Settings**  
- **Double Flower**: Determines if the flower consists of two blocks (upper and lower). *(Do not change this setting.)*  
- **Upper Half Block ID or Tag**: Specifies the block ID or tag for the upper half of the flower.  
- **Lower Half Block ID or Tag**: Specifies the block ID or tag for the lower half of the flower.  
- **Check for Enum Property**: If `true`, checks for a specific property on the block (useful for blocks with variations under the same ID).  
- **Property Name**: The name of the property being checked (e.g., `"type"`).  
- **Upper Property**: The value of the property for the upper half of the flower.  
- **Lower Property**: The value of the property for the lower half of the flower.  

## **Interaction Settings**  
- **Flower Click Action**:  
  - `1` → Can be harvested without a shear item.  
  - `2` → Cannot be harvested without a shear item.  
- **Attack on Trying Without Shear Item**: If `true`, the player will take damage when attempting to harvest the flower without the required shear item.  
- **Shear Item ID or Tag**: Specifies the item (e.g., shears) required to properly harvest the flower.  

## **Drop Settings**  
- **Drop Petal**: Determines if the flower drops petals when harvested.  
- **Drop Seed**: Determines if the flower drops seeds when harvested.  
- **Drop Item**: Determines if a custom item will be dropped instead.  

## **Flower Replacement Settings**  
- **Flower Replace Type**: Determines what happens when the flower is harvested.  
  - `1` → Simply removes the flower block.  
  - `2` → Removes the flower with particle effects.  
  - `3` → Replaces the flower with another flower type.  
  - `4` → Replaces the flower with a custom block.  
- **Replace Type**: Determines the type of flower replacement. (`6` types available)
- **Replace Upper Block ID (Flower Replace Type = 4)**: Specifies the block ID that replaces the upper half of the flower when using Replace Type `4`.  
- **Replace Lower Block ID (Flower Replace Type = 4)**: Specifies the block ID that replaces the lower half of the flower when using Replace Type `4`.  

## **Petal Settings**  
- **Flower Petal Type**: Specifies the type of petals (8 types available).  
- **Petal Name**: The name of the petal that will be dropped.  
- **Petal Color (RGB)**: Determines the petal color using Red, Green, and Blue values (0-255).  
- **Petal Random Drop Number**: If `true`, the number of petals dropped will be random within the specified range.  
- **Fixed Petal Drop Count**: If `Petal Random Drop Number = false`, this sets a fixed number of petals dropped.  
- **Min Petal Drop Count / Max Petal Drop Count**: The minimum and maximum number of petals that can drop if `Petal Random Drop Number = true`.  

## **Seed Settings**  
- **Flower Seed Type**: Specifies the type of seed (8 types available).  
- **Seed Name**: The name of the seed item.  
- **Seed Placable on Block ID or Block Tag**: Determines which block(s) the seed can be planted on.  
- **Seed Placing Type**: Determines what happens when the seed is placed (6 types available, with an additional type for placing custom blocks).  
  - `8` → Places a custom block from the **Seed Block Set** attributes.  
- **Seed Action**: Determines how the seed behaves when placed.  
  - `1` → Places the seed according to its Seed Placing Type.  
  - `2` → Immediately places the same flower it was picked from (no growth stages).  
- **Seed Upper Block Set (Seed Placing Type = 8)**: The block ID that will be placed as the upper block when using Seed Placing Type `8`.  
- **Seed Lower Block Set (Seed Placing Type = 8)**: The block ID that will be placed as the lower block when using Seed Placing Type `8`.  
- **Seed Color (RGB)**: Determines the seed’s color using Red, Green, and Blue values (0-255).  
- **Seed Random Drop Number**: If `true`, the number of seeds dropped will be random within the specified range.  
- **Fixed Seed Drop Count**: If `Seed Random Drop Number = false`, this sets a fixed number of seeds dropped.  
- **Min Seed Drop Count / Max Seed Drop Count**: The minimum and maximum number of seeds that can drop if `Seed Random Drop Number = true`.  

## **Custom Item Drop Settings**  
- **Drop Item Random Drop Number**: If `true`, the number of custom items dropped will be random within the specified range.  
- **Fixed Drop Count**: If `Drop Item Random Drop Number = false`, this sets a fixed number of items dropped.  
- **Min Drop Count / Max Drop Count**: The minimum and maximum number of custom items that can drop if `Drop Item Random Drop Number = true`.  
- **Drop Item ID**: The ID of the item that will be dropped instead of the flower.

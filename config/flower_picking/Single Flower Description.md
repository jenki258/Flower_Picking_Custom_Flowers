## **Single flower Configuration Description**  

## **Basic Settings**  
- **Double Flower**: Determines if the flower is a double-height flower. *(Do not change this setting.)*  
- **Flower ID or Tag**: Specifies the block ID or tag that represents the flower.  
- **Flower Click Action**:  
  - `1` → Can be harvested without a shear item.  
  - `2` → Cannot be harvested without a shear item.  
- **Attack on Trying Without Shear Item**: If `true`, the player will take damage when attempting to harvest the flower without the required shear item.  
- **Shear Item ID or Tag**: Specifies the item (e.g., shears) needed to properly harvest the flower.  

## **Drop Settings**  
- **Drop Petal**: Determines if the flower drops petals when harvested.  
- **Drop Seed**: Determines if the flower drops seeds when harvested.  
- **Drop Itself**: Determines if the flower drops itself as an item.  
- **Drop Item**: Determines if a custom item will be dropped instead.  

## **Flower Replacement Settings**  
- **Flower Replace Type**: Determines what happens when the flower is harvested.  
  - `1` → Simply removes the flower block.  
  - `2` → Removes the flower with particle effects.  
  - `3` → Replaces the flower with another flower type.  
  - `4` → Replaces the flower with a custom block.  
- **Replace Type**: Determines the type of flower replacement. (`16` types available)
- **Different Stages with/without Shear Item**: If `true`, the flower will have different growth stages depending on whether it is harvested with a shear item. *(Single flowers only have 3 stages.)*  
- **Replace Stage (Without Shears)**: Determines the replacement stage if the flower is harvested without shears.  
- **Replace Stage (With Shears)**: Determines the replacement stage if the flower is harvested with shears.  
- **Replace Block ID (Flower Replace Type = 4)**: Specifies the block ID that replaces the flower when using Replace Type `4`.  

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
- **Seed Placing Type**: Determines what happens when the seed is placed (16 types available).  
  - `17` → Sets a custom block from the **Seed Block Set** attribute.  
- **Seed Block Set**: The block ID that will be placed when using Seed Placing Type `17`.  
- **Seed Planting Stage**: The initial stage of the flower when the seed is planted.  
- **Seed Color (RGB)**: Determines the seed’s color using Red, Green, and Blue values (0-255).  
- **Seed Random Drop Number**: If `true`, the number of seeds dropped will be random within the specified range.  
- **Fixed Seed Drop Count**: If `Seed Random Drop Number = false`, this sets a fixed number of seeds dropped.  
- **Min Seed Drop Count / Max Seed Drop Count**: The minimum and maximum number of seeds that can drop if `Seed Random Drop Number = true`.  

## **Custom Item Drop Settings**  
- **Drop Item Random Drop Number**: If `true`, the number of custom items dropped will be random within the specified range.  
- **Fixed Drop Count**: If `Drop Item Random Drop Number = false`, this sets a fixed number of items dropped.  
- **Min Drop Count / Max Drop Count**: The minimum and maximum number of custom items that can drop if `Drop Item Random Drop Number = true`.  
- **Drop Item ID**: The ID of the item that will be dropped instead of the flower.  


# 🌸 Flower Picking Mod – Addon Creation  

This repository contains **templates and instructions** for creating addons for the **Flower Picking Mod** in Minecraft.  

## 📂 Setting Up Your Addon  

Before creating your custom flower-picking addon, follow these steps:  

1. **Navigate to the Config Folder**  
   - Open your **modpack** or `.minecraft` directory.  
   - Locate and open the `config` folder.  

2. **Create the Required Folder**  
   - Inside the `config` folder, create a new folder named:  
     ```
     flower_picking
     ```  

3. **Download Flower Templates**  
   - This repository includes **two template files** for defining custom flowers:  
     - `single_flower_template.json` → **For one-block flowers**  
     - `double_flower_template.json` → **For double-plant flowers**  

## ⚠️ Important Rules  

- **Do NOT modify** the `"Double Flower"` parameter in the **double-plant** template.  
  - If you change it, **right-clicking the flower will crash the game**!  
- **Do NOT delete any parameters** from the template files.  
  - Removing required parameters will **crash the game**.  

## 🌼 Customizing Your Flowers  

To add custom flowers:  

1. Copy the appropriate template (`single_flower_template.json` or `double_flower_template.json`).  
2. Rename the file using the following format:  
   ```
   1customflowers.json
   ```  
3. For additional custom flower files, increase the **number** in the filename by +1:  
   ```
   2customflowers.json
   3customflowers.json
   ...  
   ```  

## 📖 Parameter Descriptions  

Below the templates, you will find **detailed descriptions** of all parameters used in **single** and **double** flower definitions. Be sure to read through them to understand how to configure your flowers properly.  

## 📖 About petals & seeds

They have NBT tags that have id of block that they were picked from(Use that for crafts not just flower_picking:type_1_petal or something like this as it will just be for all flower petals that have type 1 petal in them)
As also color NBT and other stuff

## 💬 Need Help?  

If you have any questions or encounter issues, feel free to join my discord server!
https://discord.gg/bJWbUsWAWk

🌿 Happy modding! 🌿  

---

# Cyberpunk scripts etc.
  
  
- [Cyberpunk2077.ct](https://github.com/themaoci/Cyberpunk2077/blob/main/Cyberpunk2077.ct)
_Authors: C130s, Sauce_King, Conjure__, ArphonCT_  

- Edit to make Hold Button faster.  
  - Edit file: `Cyberpunk 2077\r6\config\inputContexts.xml`  
    - `disassemble_item` -> 0.01 (removes the timer of holding button to disassemble)
    - `craft_item` -> 0.01 (removes the timer of crafting item)
    - `use_item` -> 0.01 (removes the timer of using item)

- Slow Forward Motion (60% of W key)
  - Edit file `Cyberpunk 2077\r6\config\inputUserMappings.xml`
    - `LeftY_Axis` -> ADD -> `<button id="IK_X" val="0.6" overridableUI="forward"/>` (IK_X - means X key on keyboard)
    - `Acceleration_Axis` -> ADD -> `<button id="IK_X" val="0.6" overridableUI="vehicleAccelerate"/>` (IK_X - means X key on keyboard)
    - `Acceleration_Axis_Tank` -> ADD -> `<button id="IK_X" val="0.6" overridableUI="vehicleAccelerate"/>` (IK_X - means X key on keyboard)

- Performance Tweaks.
  - (Fixing Ram and VRam pools](https://www.nexusmods.com/cyberpunk2077/mods/208?tab=files) (Choose proper file coresponding to your ram value and vram value and replace files in `Cyberpunk 2077\engine\config\memory_pool_budgets.csv`
  - this method isnt working for older win 10 with threadripper and 2080 Super what i found is to zero everything just replacing all values with `0` to let game choose dynamickly how much it needs and then set `PoolCPU` to half of your ram capacity for 32GB Ram it is `16384MB`
  - AMD Multithreating fix: 
    Replace `75 30 33 C9 B8 01 00 00 00 0F A2 8B C8 C1 F9 08` with `EB 30 33 C9 B8 01 00 00 00 0F A2 8B C8 C1 F9 08` in `Cyberpunk 2077\bin\x64\Cyberpunk2077.exe` using any hex editor (best way will be to search and replace any occurance)

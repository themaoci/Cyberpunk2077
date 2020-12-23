# Cyberpunk scripts etc.
  
  
- [Cyberpunk2077.ct](https://github.com/themaoci/Cyberpunk2077/blob/main/Cyberpunk2077.ct)
_Authors: C130s, Sauce_King, Conjure__, ArphonCT_, TheMaoci  

- [Cyberpunk2077_v2.ct](https://github.com/themaoci/Cyberpunk2077/blob/main/Cyberpunk2077_v2.ct) - [source](https://www.unknowncheats.me/forum/other-fps-games/430703-cyberpunk-2077-table.html)

- Edit to make Hold Button faster.  
  - Edit file: `Cyberpunk 2077\r6\config\inputContexts.xml`  
    - `disassemble_item` -> 0.01 (removes the timer of holding button to disassemble)
    - `craft_item` -> 0.01 (removes the timer of crafting item)
    - `use_item` -> 0.01 (removes the timer of using item)
  - File to copy paste (dissasemble and craft) [inputContexts.xml](https://github.com/themaoci/Cyberpunk2077/blob/main/inputContexts.xml)

- More option settings [settings folder to replace](https://github.com/themaoci/Cyberpunk2077/blob/main/settings.7z)

- Slow Forward Motion (60% of W key)
  - Edit file `Cyberpunk 2077\r6\config\inputUserMappings.xml`
    - `LeftY_Axis` -> ADD -> `<button id="IK_X" val="0.6" overridableUI="forward"/>` (IK_X - means X key on keyboard)
    - `Acceleration_Axis` -> ADD -> `<button id="IK_X" val="0.6" overridableUI="vehicleAccelerate"/>` (IK_X - means X key on keyboard)
    - `Acceleration_Axis_Tank` -> ADD -> `<button id="IK_X" val="0.6" overridableUI="vehicleAccelerate"/>` (IK_X - means X key on keyboard)

- Performance Tweaks.
  - 1.05 patch fixed those issues (multithreating, pool utilizations)

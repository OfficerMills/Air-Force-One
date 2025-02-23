# Boeing VC-25A

## Air Force One
------------------------------------------------------
![Downloads](https://img.shields.io/github/downloads/officermills/Air-Force-One/total?logo=Boeing&logoColor=%2387CEEB&label=Downloads&labelColor=%2387CEEB&color=%2387CEEB)

#### Credits:
FSX  
Rockstar Games  

Single Player Conversion & Interior Edits by **[SkylineGTRFreak](https://www.gta5-mods.com/users/skylinegtrfreak)**  
FiveM Conversion, Handling Edits, Photos by **[OfficerMills](https://discord.gg/OfficerMills)**
![Officer Mills GitHub stats](https://img.shields.io/github/followers/officermills)

------------------------------------------------------

### Mod Features
- Working flaps, landing gear, ailerons, rudder, spoilers, and elevators  
- Detailed cockpit with working gauges  
- Detailed lower entrance and presidential cabin  
- Lights  
- Custom collision mesh (allows bullet holes and walking on the vehicle)  
- Burn effects  

### Notes  
- If the lights sometimes don’t work, try switching the camera view a few times.  
- Door Commands:  
  - **Left front door**: Opens the main deck door (you can exit through here but **not** enter).  
  - **Right front door**: Opens the lower entrance hatch.  
  - **Boot/Trunk**: Opens the lower entrance stairway.  
  - **Rear doors**: Open the inner spoilers (no real function, but can be opened for screenshots).  

------------------------------------------------------
# Photos
| Exterior Day | Exterior Night | Pilots Suite | Cockpit |
|--------------|--------------|--------------|--------------|
| ![Air Force One 1](https://i.imgur.com/EL8JA9H.jpg) | ![Air Force One 2](https://i.imgur.com/PA5GRZn.png) | ![Air Force One 3](https://i.imgur.com/HI2lihh.png) | ![Air Force One 4](https://i.imgur.com/HI2lihh.png) |

------------------------------------------------------

# FiveM Installation
1. Navigate to your FiveM server’s `resources` folder.  
2. Open the `FiveM` folder inside this resource and grab the `airforce1` folder, then drag it into your `resources` folder.  
3. Add `ensure airforce1` to your **`server.cfg`** file.  
4. Restart your server.  
5. Test the aircraft:  
   a) You can spawn the aircraft by opening your client console (F8),  
      then typing the command `car afo` and pressing **Enter** or using next option.  

   b) Open your chat window (default "T" key) and type `/car afo`,  
      then press **Enter**.
6. If you would like for this vehicle to be "ownable" by yourself and/or player you will need to navigate to `qb-core/shared/vehicles.lua` and paste in the following line:
    ```lua
    { model = 'afo',     name = 'Boeing VC-25A Air Force One',      brand = 'Boeing',       price = 3900000000,     category = 'planes',        type = 'plane',     shop = 'none' },
    ```          

------------------------------------------------------

# Single Player Installation
1. Open the `Single Player` folder and drag the `airforce1sp` folder into `[Gamefolder]\update\X64\dlcpacks\`.  
2. With OpenIV, open `[Gamefolder]\update\update.rpf\common\data\dlclist.xml` using your preferred code editor (VSCode/Notepad++, etc.) and add the following line:
   ```xml
   <Item>dlcpacks:\airforce1sp\</Item>
   ```
3. You’re done! Now you’ll need a trainer with a “spawn by name” function (e.g., Enchanted Native Trainer). To spawn this aircraft, type: `afo`

I advise using a **Mods** folder (see OpenIV documentation) and making a backup beforehand. I take no responsibility for anything that might go wrong.

------------------------------------------------------

## Contributions
If you've found a bug, you can go ahead and create an [issue](https://github.com/OfficerMills/Air-Force-One/issues).  
If you've improved the resource, feel free to make a [pull request](https://github.com/OfficerMills/Air-Force-One/pulls)!

## License
Copyright © 2025 Officer Mills.  
This project is [GNU GPL v3.0](https://github.com/OfficerMills/AirForce1/blob/main/LICENSE) licensed.

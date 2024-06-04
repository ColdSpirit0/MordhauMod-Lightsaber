# Lightsaber

Adds four lightsabers: blue, green, pink and red.

You can change stance by pressing R.


## How to install
1. Install [Equipment Fix](https://github.com/ColdSpirit0/MordhauMod-EquipmentFix) mod.
2. Create the directory `.../MORDHAUEditor/Mordhau/Mods/Lightsaber`.
3. Move to the directory and open the command prompt.
4. Write `git clone https://github.com/ColdSpirit0/MordhauMod-Lightsaber.git .`


## Config example

```ini
[/Script/Mordhau.MordhauGameSession]
Mods=3754883 ; https://mod.io/g/mordhau/m/lightsaber

[EquipmentLoader]
LoadEquipment=/Lightsaber/Blueprints/BP_LightsaberBlue.BP_LightsaberBlue_C
LoadEquipment=/Lightsaber/Blueprints/BP_LightsaberGreen.BP_LightsaberGreen_C
LoadEquipment=/Lightsaber/Blueprints/BP_LightsaberPink.BP_LightsaberPink_C
LoadEquipment=/Lightsaber/Blueprints/BP_LightsaberRed.BP_LightsaberRed_C
```
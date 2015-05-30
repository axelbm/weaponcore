# Weaponcore
A core for the Expression 2 in Gmod

function list:


`void entity:plyGive(string weaponid)`

`void entity:plyGiveAmmo(string ammotype, number count)`

`void entity:plySetAmmo(string ammotype, number count)`

`void entity:plySetActiveWeapon(string weapon)`

`void entity:plySetActiveWeapon(entity weapon)`

`void entity:plyDropWeapon(string weapon)`

`void entity:plyDropWeapon(entity weapon)`

`void entity:plyStripWeapons(string weapon)`

`void entity:plyStripWeapons(entity weapon)`

`void entity:plyStripWeapons()`

`void entity:plyStripAmmo()`

`void entity:plySetClip1(ammo)`

`void entity:plySetClip2(ammo)`

`entity entity:getWeapon(string class)`

`number entity:hasWeapon(string weapon)`

`void runOnWeaponSwitch(activate)`

`number weaponSwitchClk()`

`entity lastWeaponSwitchPlayer()`

`entity lastWeaponSwitchOld()`

`entity lastWeaponSwitchNext()`

`void runOnWeaponEquip(activate)`

`number weaponEquipClk()`

`entity lastWeaponEquip()`

SafeZoneBarrels
===============



In compiles.sqf

 ADD

SafeZoneBarrels =           compile preprocessFileLineNumbers "sys\SafeZoneBarrels.sqf"; //path whereever you like

___________________________________________________________________________________________________________________
In mission.sqm

ADD

[player] spawn SafeZoneBarrels;

at each tradezone so it looks like


expActiv="[""Black Market"",true,""enter""] spawn player_traderCity; canbuild = false; [player] spawn SafeZoneBarrels;";

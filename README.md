# ExileServer-ClearBuffer-Fix
This fixes some broken Vanilla code that skipped elements in the ExileSystemPlayerSaveASYNC and ExileServerVehicleSaveQueue on clearing buffers on server restart.
Which is rather bad because it can cause loss of gear/vehicle rollback or allow duping!

# Installation 
* Replace @ExileServer\addons\exile_server\code\ExileServer_system_rcon_event_clearBuffers.sqf and repack your exile_server.pbo

# ATRAGMX_PRESETS
To import these presets, you need to run:
```sqf
profileNamespace setVariable ["ACE_ATRAGMX_gunList", ThePresetArray];
```
Where `ThePresetArray` is the text from the preset.sqf file. Be aware that you may need to reload the mission to see the changes.

If you want to contribute a preset, you can export your ATRAGMX presets by running:
```sqf
profileNamespace getVariable ["ACE_ATRAGMX_gunList", []];
```
Then, you can copy the output from the `profileNamespace getVariable "ACE_ATRAGMX_gunList";` command and add it to the preset file.

Please follow the naming convention of ['mod name' 'gun name' 'ammo name'] for the preset title, and make sure to group each preset by mod.

Credit to ACE3 discord user PabstMirror for the commands.

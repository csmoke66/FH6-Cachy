RUNE ported from amg_ags_x64.dll to version.dll

1. Delete amd_ags_x64.dll, rename amd_ags_x64_rne.dll to amd_ags_x64.dll
3. Delete xgameruntime.dll, rename xgameruntime.rne to xgameruntime.dll (maybe possibly optional, I get a save error with this dll)
2. Move version.dll and version_rne.dll to the game directory
3. Add DLL overrides version=n,b

Tested on proton-cachyos-11.0-x86_64. Requires xbox account sign-in once game is booted, I'm not sure what's wrong with the xgameruntime patch.

![wow](https://i.imgur.com/YeykINT.png)

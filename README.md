# DO NOT LINK DIRECTLY TO THIS REPO! PLEASE USE THE WINCLASSIC POST LINK AT THE START OF THIS README.
# explorer7 - ex7forw8, modernized
READ THE WINCLASSIC POST IF YOU CAME HERE FROM AN EXTERNAL LINK: https://winclassic.net/thread/2588/explorer7-windows-explorer-10-11

This is the official github for explorer7 releases.\
DO NOT USE THIS REPO TO REPORT ISSUES. (you can't either way)\

Discord Server: https://discord.gg/d3yVmW4xgr

## Registry keys

These keys are located under `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`.

| Name | Type | Description |
| ---- | ---- | ----------- |
| Theme | REG_SZ | Name of the theme to use. This is relative to the directory. For example, "aero" will use the theme at "explorer7\theme\aero.msstyles". If this is not specified, aero will be used. |
| DisableComposition | REG_DWORD | When set to 1, explorer7 will act as if the Desktop Window Manager is not running. |
| ClassicTheme | REG_DWORD | When set to 1, explorer7 will use the Windows Classic theme. |



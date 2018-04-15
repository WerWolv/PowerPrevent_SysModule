# PowerPrevent_SysModule

This project is a modified version of the Luma3DS Rosalina menu SysModules with an added power button safety mechanic.
To prevent acidental pressing of the power button during gameplay, it is now required to hold the START button while pressing the power button in order to shutdown the console.

All credit goes the to AuroraWright and his team who built the fantastic [Luma3DS](https://github.com/AuroraWright/Luma3DS/) CFW.

## Usage
1. Enable **Enable loading exteral FIRMs and modules** in the Luma3DS configuration menu
2. Download the rosalina.cxi file and put it in the SDHC:/luma/sysmodules/ folder. Don't rename the file or it won't be able to load.
3. To shutdown the 3DS now, the START button has to be held down before pressing the power button. Otherwise the button will be completely ignored.

## Limitations

For now the only way to load a system module in Luma3DS is by replacing an existing one. This is the reason why the entire Rosalina code is included. For now this is purely an addition to Rosalina. 


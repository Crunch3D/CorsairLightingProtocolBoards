# Corsair Lighting Protocol Boards
Arduino board definitions for use with the [Corsair Lighting Protocol](https://github.com/Legion2/CorsairLightingProtocol) library.
These board definitions have modified USB settings so they can be used to simulate corsair devices.

## Install CLP Boards in Arduino
All boards can simply be installed in Arduino IDE via the Boards Manager.

package index URL:
```
https://raw.githubusercontent.com/Legion2/CorsairLightingProtocolBoards/master/package_Legion2_CorsairLightingProtocolBoards_index.json
```

1. Open the **Preferences** of the Arduino IDE.

   ![File->Preferences](images/open-preferences.png)
1. Add the package index URL above in the **Additional Boards Manager URLs** field, and click OK.

   ![Additional Boards Manager URLs Pop-up](images/add-package-url.png)
1. Open the **Boards Manager** by opening the menu Tools->Board->Board Manager...

   ![Tools->Board->Board Manager...](images/open-boards-manager.png)
1. Search and install **Corsair Lighting Protocol Boards**

   ![install boards in Board Manager](images/install-boards.png)
1. For some of the boards you must install additional defintions: [SparkFun Boards](https://github.com/sparkfun/Arduino_Boards#installation-instructions), [Hoodloader2 Boards](https://github.com/NicoHood/HoodLoader2/wiki/Software-Installation#2-installing-board-definitions).
   Make sure you add the additional board urls each on a new line and don't remove the already existing ones.

   ![all additional boards urls](images/additional-boards-urls.png)

## How to use these boards in Arduino
The CLP Boards can now be used in Arduino IDE.
The following is only an example on how to use the boards, it's not required for the installation.

1. Select one of the boards under Corsair Lighting Protocol Boards in Tools->Board menu

   ![Tools->Board menu](images/select-board.png)
1. Select one of the devices from corsair under Tools->Device

   ![Tools->Device](images/select-device.png)
1. Select COM port under Tools->Port

   ![Tools->Port](images/select-port.png)
1. Compile/Upload as usual

## License
This project is licensed under the Apache License Version 2.0.

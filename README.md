# bluetooth-module-indicator [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Ubuntu debian package deployment of a Menubar indicator for direct display of bluetooth modules' transparent app registers.
Compatible with generic modules such as JDY-16, HC-08.

## Installation
```
sudo add-apt-repository ppa:mihaigalos/ppa
sudo apt-get update
sudo apt install bluetooth-module-indicator
netatmo-indicator &
```

## Removal
```
sudo apt remove --purge bluetooth-module-indicator
```

## Screenshots
![alt text](screenshots/BluetoothModuleIndicator.png)

###### Sources
```
git clone --recursive https://github.com/mihaigalos/bluetooth-module-indicator.git
```

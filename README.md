# DataVu Driver Core
An Arduino core for Plessey's DataVu Development Kit driver. The This core allows you to use and program the driver board over USB using the Arduino IDE.

This core is based off MiniCore: https://github.com/MCUdude/MiniCore


## How to install
#### Boards Manager Installation
This installation method requires Arduino IDE version 1.6.4 or greater.
* Open the Arduino IDE.
* Open the **File > Preferences** menu item.
* Enter the following URL in **Additional Boards Manager URLs**:

    ```
    https://raw.githubusercontent.com/Plessey/DataVuBoard/master/package_DataVuBoard_index.json
    ``` 

* Open the **Tools > Board > Boards Manager...** menu item.
* Wait for the platform indexes to finish downloading.
* Scroll down until you see the **DataVu** entry and click on it.
* Click **Install**.
* After installation is complete close the **Boards Manager** window.

#### Manual Installation
Click on the "Download ZIP" button in the upper right corner. Exctract the ZIP file, and move the extracted folder to the location "**~/Documents/Arduino/hardware**". Create the "hardware" folder if it doesn't exist.
Open Arduino IDE, and a new category in the boards menu called "DataVu Driver" will show up.
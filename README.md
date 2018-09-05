# adb-right-swipe
The script uses adb shell to send a right swipe command to an android device. 
## Usage:
1. Install adb shell on the computer that will be used to run the python script.
2. On the android device, turn on developer mode. Under "Developer options", enable "USB debugging".
3. Connect your android device to your computer.
4. Open terminal on your computer and run "adb devices" to make sure that your device is connected and accesible via adb.
5. Run the python script
```
python right-swipe.py [amount of times to swipe]
```
e.g. to swipe 100 times run
```
python right-swipe.py 100
```

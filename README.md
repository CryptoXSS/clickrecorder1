# clickrecorder
Small script to record the positions of mouse clicks and repeat them automatically.
![Snapshot of GUI](./docs/gui.png)
## Features
- Record pattern of mouse clicks and repeat it infinitely
- Either manually set delays between clicks or also record them
- Supports left/right click only
- Save and load click patterns
- Set inital delay before the script starts clicking
- (Optionally) Mimick human behavior by moving the mouse along a random Bezier curve and not clicking pixel-perfectly
- Scroll to stop the script from clicking
- Currently, the upper speed limit is about 150 clicks per second if the delay is set to 0.

## Dependencies
- Python 3.6+
- tk
- pyautogui
- pynput
- numpy
- apt install python
- pip install scipy
- sudo apt-get install python-tk
- sudo apt-get install python3-tk

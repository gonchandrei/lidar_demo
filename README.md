XV Lidar Controller Visual Test

Requirements:

- python 2.7
- pyserial
- vpython

Usage:

1. Edit the lidar script and set com_port to point your Teensy
2. Connect up to controller board
3. Launch the python script
4. The program starts out showing the data in a horizontal plane which doesn’t look like much.  Click into the image and drag the pointer to adjust the point of view.
5. Proceed to move objects in out out of the path of the lidar for enjoyment.
6. Commands:
	- "o": Toggle outer line
	- "l": Toggle rays
    - "p": Toggle points
    - "i": Toggle intensity
    - "j": Toggle rpm
    - "k": Toggle errors
    - "m": Toogle motor
    - "q": Quit
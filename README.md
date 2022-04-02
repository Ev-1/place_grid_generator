# place_grid_generator
Small script for creating grid overlays with coordinates to aid with creating pixel art on r/place.



# how to "install"
create a virtual environment
 - `python -m venv venv`


Activate the virtual environment
 - Windows(powershell): `venv\Scripts\Activate.ps1`
 - Windows(command prompt): `venv\Scripts\Activate.bat`
 - Linux(bash): `source venv/bin/activate`


install dependencies
 - `python -m pip install -r requirements.txt`


run
 - `python main.py`

 That should generate an image file with coordinates.

if you want to modify the size of the grid go to main.py and edit
the following parameters to suit you.

top_left_x_offset: the offset in the x direction from the top
top_left_y_offset: the offset in the y direction from the top

pixel_magnifier: how many pixels should be used to represent a single pixel in the final image

region_width: the width of the grid region you wish to generate
region_height: the height of the grid region you wish to generate.

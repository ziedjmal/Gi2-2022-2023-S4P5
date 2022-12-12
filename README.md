# Gi2-2022-2023-S4P5
Arduino:
	upload the code (cnc.ino) to arduino using arduino IDE (downoald any missing library to make the code work
G-Code:
	Build images
		Download and install Inkscape (0.48.5 version)
	export images to gcode files
		Extract (inkscape-unicorn-master) and add (inkscape-unicorn-master/src) to (Inkscape/plugins)

Processing IDE Program :
	download processing-2.2.1
	download cnc.pde
	open cnc.pde with processing
	launch code 
		keys functions:
			p :select port
			0 :initialize zero point
			g :select gcode(exported from inkscape) and start cnc

all necessary files with requirements version are included in this repository 
but if there are any problem these are the origin sources

inkscape-0.48.5 : https://inkscape.org/release/inkscape-0.48/?latest=1
inkscape-unicorn : https://github.com/martymcguire/inkscape-unicorn
processing-2.2.1 :https://processing.org/download

(Important: Use the listed versions)

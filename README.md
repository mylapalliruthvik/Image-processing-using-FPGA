# Image-processing-using-FPGA
First, we need a PYNQ board,HDMI cable,An ethernet for communication with PC,web cam,External moniter,and Jupiter notebook.
Let us see the process:
Connect USB nd Ethernet cable from PC to FPGA.
Insert the Micro SD card loaded with the EDGE-Z10/EDGE-Z20 image into the Micro SD card slot underneath the board.
Set the J2/Boot jumper to the kit SD position and turn on the kit.
Now, in our PC, go to "putty" software and set the baud rate to 115200 to view the boot screen.
As the USB power from PC is not enough for webcam demo, in the mean time, connect external 5v USB adaptor to the board or use 5v power supply at DC socket.
in the book screen, type 'ifconfig' to view the board's ip address.
copy that ip address.
Assign your computer a static IP address.
Give the copied ip address there, or give the ip address 192.168.2.11(this should be done for the etherenet in network settings).
Now, go to browser and type "pynq:9090".
The process is 'xilnix'.
Then go to the file named "base", and then "video", and then "opencv_face_detect_webcam.ipynb".
Run the code
Now, the detected face is displayed on the external moniter s well as in the jupiter window.

# URX-jupiter-notebook

This is an interactive tutorial on python URX library for Universal Robots


How to run:

You will need a Robot or a Simulator (https://www.universal-robots.com/download/?option=16451#section16447)

-Setup network connection between PC and UR-robot (I prefer 10.0.0.2 for robot and 10.0.0.3 for PC)

-Turn-on Ethernet in Robot's Polyscope Installation tab.

-Ping the connection (cmd > ping 10.0.0.2)



-Download and setup Anaconda (Python 3.х version) https://www.anaconda.com/download/

-Download URX library from https://github.com/jkur/python-urx/tree/SW3.5/urx to "drive\path-to-anaconda3\Lib\site-packages\urx"
Attention: RTDE protocol had changed in Polyscope 3.5, so you will need to use given fork instead of original source.
if you have got URX from pip, you have to replace all library files from link above.


-Download the last version of this notebook https://github.com/LukeSkypewalker/URX-jupiter-notebook


-Make a Shortcut (with YOUR OWN path to Anaconda3 and URX-notebook:

"C:\path-to\Anaconda3\python.exe" "C:\path-to\Anaconda3\cwp.py" "C:\path-to\Anaconda3" "C:\path-to\Anaconda3\python.exe" "C:\path-to\Anaconda3\Scripts\jupyter-notebook-script.py" "C:\path-to\URX-jupyter-notebook"

..and run it! 

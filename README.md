# UDP-Streaming  
### Modules needed.
* openCV  `pip3 install python-opencv`  
* libturbojpeg `sudo apt-get install libturbojpeg`  
* Numpy (installed with openCV)  

## To Run.

* On a terminal, enter `python3 server.py --port 10080` for server. (Camera will start).
* On a new terminal, enter `python3 client.py --host localhost --port 10080` (The output will be shown in a new window).  


Pressing 'q' on the client side within the CV2 window will isue a quit command to the client and server.

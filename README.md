# Hawkeye4  
It is essentially the same as Hawkeye3 but with the additional HW to synchronously capture the   
frames and assemble the output video.  
The PC capture sw is a newer version from similar to Hawkeye3 but it has the mouse click sennse  
and the video frame grab plus the output video assembly.  
## Operation  
It is pretty simple.  
Set up the projector and the camera and load the film in. 
Turn the LED light on.  
Connect the camera USB cable to the PC.  
Connect the control cable (mouse emulator) to another USB port on the PC.  
Go to 
SankyoSyncCapture\CapSample_video\CapSample\bin 
Run  
CapSample.exe  
![image](https://github.com/vintagefilmography/Hawkeye4/assets/48537944/0e38c20a-a931-4a20-954c-7579cbf18d19)  
Leave the configuration as is.  
![image](https://github.com/vintagefilmography/Hawkeye4/assets/48537944/1b6f1428-f27b-4eea-a02e-76c01fba1847)  
Click on Video Capture Device  
![image](https://github.com/vintagefilmography/Hawkeye4/assets/48537944/a851c7ad-c51b-4e0e-9479-03e09142596b)  
And then on Camera Control  
Set exposure to manual.  
You will have to use the exposure slider running teh scan to set to to your liking.  
Note: For some film clips auto exposure may work ok. 
Click OK.  
Click OK in the Camera Configuration window.  
The Main window will pop up with the camera preview.
![image](https://github.com/vintagefilmography/Hawkeye4/assets/48537944/6276b9b1-3582-4fd8-95ba-6d4a134eed80) 
Position the mouse cursor over the eFrame button and run the projector. 
Make sure the projector control switch is set to LAMP and the espeed set to around 8 FPS.   
The captured frames will be displayed in the output window.  
Close the Main window when done.  
The output filee ewill bee in the directory specified in the Camera aconfiguration window.
The name of the filee is hardcoded to "test.mp4" in this first release of the software but is will  
be changed to pick up whatever name is specified in the configuration window.
Change the output video file name eto something else to preevent file overwrite in the next capture session.




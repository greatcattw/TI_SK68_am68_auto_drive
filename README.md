# TI_SK68_am68_auto_drive
Using Ti am68 to implement toy car auto drive.  
Using TI am68 to detect signs for auto driving.  

I don't konw why I can not add toy traffic corn to TI_SK68 by web model composer. (2024/04)  
Work around, short term solution, using small bottle instead of toy traffic corm.  
The native model, ONR-OD-8200-yolox-nano, is good at detecting bottle.  
Thus, my plan,  
(1)The computer wget jpg file from WiFi camera on toy car.   
(2)The computer ask TI_SK68 to detect all bottles X1Y1X2Y2 in the jpg file.  
(3)Then computer controls toy car over bluetooth.  

![pic](pic/pic1.jpg)<br><br><br>

# IN PROGRESS ...

/*
	input -> จั้ม GND
	output ->จั้ม ไฟ
*/


motor1 ,y21
motor2 ,y25
output _ plum  -> y11,12,13,14,15
y11-BL	->up1	
y14-BR  ->down1

y15-TL  -> up2
y12-RT  -> down2

y13-black

sensor pump>>

<left  pump> 
top   x10
button 1  -> x14 left หนา
button 2  -> x13 Right บาง
<left  pump> 


<Right  pump> 
top   x15
button 1  -> x11 left หนา
button 2  -> x12 Right บาง
<Right  pump> 

*.  pump_type (size ของ Bearing)

pump_type = 1 -> บาง
pump_type = 0  -> หนา










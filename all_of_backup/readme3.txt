arm_keeper  25-open 24-close
arm_rotate  23-ซ้าย  22-ขวา
arm_pullup  4-up , 7-down
arm_slide   6-font,1-back

slide_main   left-26 , right-27




--------------------------------
plum sensor

buttom 14   top    10

-------------------------------
output y0-y7
output _ plum  -> y11,12,13,14,15
y11-BL	->up1	
y14-BR  ->down1

y15-TL  -> up2
y12-RT  -> down2

y13-black

output _ motor -> onตลอด -> 21,25ใช้พร้อมกัน

y0->main_slide
y1->rotate1
y2->up_down1
y3->font_back1
y6->keeper


top_sensor_2 -> 15
down_sensor_2 -> 12


//----------------zone2 -------------
arm_keeper  21-open 20-close
arm_rotate  17-ซ้าย  16-ขวา
arm_pullup  3-up , 2-down
arm_slide   5-font,0-back


y5->rotate2
y7->up_down2
y4->font_back2
y20->keeper 2

4,5,7,20












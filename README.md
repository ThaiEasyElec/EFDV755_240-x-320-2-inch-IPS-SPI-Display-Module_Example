***ตัวอย่างการใช้งานบอร์ด Raspberry Pi Pico ร่วมกับ จอ TFT 2 นิ้ว 320x240 ST7789***
- ทำการติดตั้ง Board package ของบอร์ด Raspberry Pi Pico โดยไปที่ Board manager 
![image](https://user-images.githubusercontent.com/8803501/116512926-03405880-a8f3-11eb-8905-882b9dafd8aa.png)


- ทำการติดตั้ง Library ที่ชื่อว่า Adafruit ST7735 and ST7789 Library โดยสามารถติดตั้งผ่าน Library Manager บน Arduino IDE ได้เลย 
![image](https://user-images.githubusercontent.com/8803501/116513024-2b2fbc00-a8f3-11eb-94be-5bbba5c4271a.png)


-  ทำการติดตั้ง Library ที่ชื่อว่า Adafruit GFX library 
-  ![image](https://user-images.githubusercontent.com/8803501/116513568-ff610600-a8f3-11eb-97d4-8b883eeb4982.png)


- ทำการคัดลอกโค้ดตัวอย่างและทำการอัพโหลดลงบอร์ด Raspberry Pi Pico โดยการกดปุ่ม BOOTSEL ค้างไว้ก่อนเสียบสาย Micro USB จากนั้นเลือกบอร์ดเป็น Raspberry Pi Pico แล้วทำการอัพโหลดโค้ด (ไม่ต้องเลือก comport)

การต่อวงจร (Connection)

![image](https://user-images.githubusercontent.com/8803501/116512717-a644a280-a8f2-11eb-856f-e478806f7ad3.png)

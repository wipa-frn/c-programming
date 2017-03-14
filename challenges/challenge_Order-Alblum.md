ชิตพลต้องการเปิดร้านพรีออเดอร์อัลบั้ม จึงอยากเขียนโปรแกรมที่สามารถรับจำนวนอัลบั้ม ซึ่งเป็นจำนวนเต็มบวก รับอักขระเพื่อเลือกรูปแบบการจัดส่งและ 
แสดงราคาสินค้า ค่าจัดส่ง และสรุปราคาสินค้ารวมที่ต้องจ่าย ถ้ามีการสั่งของมากกว่า 1 ชิ้น ให้เพิ่มค่าจัดส่ง ชิ้นต่อไปชิ้นละ 10 บาท ถ้ามีโค้ดส่วนลด
จะลดค่าจัดส่งได้ 60 บาท 

<B>หมายเหตุ</B> 

-ถ้าพิมพ์ค่าผิด ให้พิม Error แล้วรับค่าใหม่

-R,E เป็นตัวใหญ่หรือตัวเล็กก็ได้

-โค้ดส่วนลดคือ CHITTA (ตัวใหญ่เท่านั้น) ถ้าใส่โค้ดผิดให้พิมพ์ "Sorry! your code incorrect." และการใส่โค้ดจะให้ใส่ครั้งเดียวเท่านั้น

-ถ้าไม่มีโค้ดส่วนลด ให้สรุปราคาได้เลย

<B>ตัวอย่าง</B>
~~~
Please enter amount to order.

NCT #127 - The 1st Mini Album [530 Baht] : 0
NCT#127 LIMITLESS - The 2nd Mini Album [690 Baht] : 1
NCT DREAM - The First [490 Baht] : 1

You would like to send by REG (60 Baht) or EMS (80 Baht)?
Please enter your char [R/E] : R

Do you have code for discount delivery charge? [Y/N] : Y
Please enter your code : CHITTTA

Sorry! your code incorrect.

==================================================
-Total order is 2 pices 1180 baht.
-Total delivery charge is 70 baht.

#Total price of the order is 1250 baht.
==================================================
---THANK YOU!---
~~~

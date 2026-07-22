2996 - [LEARNING LOGS] สลับตัวอักษร

544893	

Pass

15-30 minutes

โจทย์ให้ผมสร้างโปรแกรมที่รับอักขระ 5 ตัว แล้วนำมากลับจากหลังไปหน้า

Input:
ข้อความตัวอักษรอังกฤษยาว 5 ตัวอักษร

Output:
แสดงผลข้อความตัวอักษรภาษาอังกฤษแบบกลับด้านเป็นตัวพิมพ์เล็กเท่านั้น

Constraints:
โจทย์บอกว่าต้องรับแค่ไม่เกิน 5 อักขระเท่านั้น ผมจึงต้องเขียนข้อกำหนดเพื่ไม่ให้โปรแกรมแปลงเกิน 5 อักขระ

Step 1: รับ input จาก user
Step 2: ใช้ if กำหนดให้ความยาวตัวหนังสือน้อยกว่าหรือเท่ากับ 5
Step 3: ถ้าใช่ให้พิมพ์ให้พิมตัวหนังสือแบบสลับให้ตัวแรกมาอยู่ด้านหน้าเรียงไปจนถึงตัวสุดท้าย

ตอนแรกผมไม่รู้ว่าต้องทำให้พิมพ์เล็กยังไง ผมเลยพิมพ์ลงไปในโค้ดว่า lowercase vs code เลยขึ้น suggestion มาให้ว่า .lower() นั้นจึงเป็นวิธีสุดท้ายของผม

test case 1:
ลองเลือกเป็นชื่อตัวเองก่อนเพราะมี 5 ตัวพอดี
input: STAMP
output: pmats

test case 2:
ลองชื่อจริงผมเพราะมันยาวกว่า 5 ตัว
input: Supakit
output: kapus

test case 3:
ลองเลือก test case จากที่เค้าให้มา
input: harry
output: yrrah

ได้ถามเพื่อน TA ผู้สอน หรือบุคคลอื่นเพื่อขอความช่วยเหลือในโจทย์นี้หรือไม่
: Yes

ใครช่วยคุณ
: TA

เขาช่วยอะไร
: ผมสอบถามเรื่องการใช้ suggestion ใน vs code ว่าควรเขียน AI_REFLECTION ไหม
คุณยังทำอะไรด้วยตนเอง
: ผมเขียนแผนแรกของตนเอง เขียนและทดสอบ code สุดท้ายใน VS Code ออกแบบ test cases เอง 2 อัน และส่งเข้า OJ ด้วยตนเอง

คุณคัดลอก code จากคนอื่นหรือไม่
: No

Statement	                                                                            Yes/No
I wrote this submission in my own words.	                                               Yes
I understand my final code.	                                                               Yes
I recorded the real OJ status.	                                                           Yes
I did not copy AI-generated text directly into this file.	                               Yes
I did not copy code from another person.	                                               Yes
If I received human help, I disclosed it in this file.	                                   Yes
I submitted the final code to the OJ by myself.	                                           Yes
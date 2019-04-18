![prepro logo](README/logo-banner.png)
# Introduction to Pre Programming 2019
สวัสดีครับน้อง ๆ ❤️
<br>
พี่ ๆ ก็ขอต้อนรับน้อง ๆ อีกครั้งนึงนะครับ Repo นี้จะบอกเกี่ยวกับกำหนดการและข้อมูล Pre-Programming Preparatory Course ของปี 2019 นะครับ โดยการอัปเดตเรื่องกำหนดการและข้อมูลต่าง จะใช้ Repo นี้เป็นตัวหลักนะครับ
<br>
<br>
คอร์สนี้จะเป็นเรื่องการใช้ Algorithm และ Basic Programming ซึ่งภาษาหลักของเราที่จะใช้นั้นก็คือ Python นั้นเอง โดยทั้ง 2 อย่างนั้นจะเป็นพื้นฐานหลักในวิชา Problem Solving in Information Technology (PSIT) ในปี 1 เทอม 1

# กำหนดการ Pre-Programming

|วันที่ 8 พฤษภาคม - 19 พฤษภาคม 2019|วันที่ 20 พฤษภาคม - 7 มิถุนายน 2019|วันที่ 10 มิถุนายน - 5 กรกฎาคม 2019 |
|:-------:|:----:|:-------:| 
|รับสมัครน้อง ๆ เข้า Course Pre-Programming<br>(รับสมัครผ่านทาง Google Form)|Pre-Programming รอบ Online<br>(ผ่านระบบ eJudge)|Pre-Programming รอบ Onsite<br>(ณ คณะเทคโนโลยีสารสนเทศ)|
|Status: `INACTIVE` | Status: `INACTIVE` | Status: `INACTIVE`|

> เปิดรับสมัครเร็ว ๆ นี้

# What is eJudge?
![ejudge logo](README/ejudge.png)

น้อง ๆ คงสงสัยว่าระบบ eJudge ที่พี่กล่าวถึงนั้น คืออะไร ?

ระบบ eJudge เป็นระบบ Grader ชนิดหนึ่ง ที่จะรับโปรแกรมของน้อง ๆ มา แล้วรัน โดยการใส่ค่า Input ที่พวกพี่ ๆ ที่ออกโจทย์เขียนเอาไว้ และรับค่า Output ที่ผ่านโปรแกรมนั้น ๆ ออกมา
โดยระบบจะสามารถเช็คได้ถึง

* **ความมีระเบียบ** ในการเขียนโปรแกรม (คุณภาพ)
* **ความคล้ายคลึงใน Algorithm** ในโปรแกรมน้อง ๆ กับเพี่อนของน้อง ๆ
* **ความถูกต้องในผลลัพท์** ที่ออกมาจากโปรแกรมที่น้องๆเขียนมา
* **เก็บคะแนน** และเก็บไฟล์ที่น้องเคยส่งมาทั้งหมด

> [ E-Judge Grader ITKMITL ](https://ejudge.it.kmitl.ac.th/)

โดยน้อง ๆ ก็จะเจอกับระบบนี้ไปอีกนาน เพราะน้องต้องเรียนกับมัน สอบกับมัน ทำ Quiz กับมัน ดังนั้น พี่อยากให้น้องทำความเข้าใจและทำตัวให้ชินไปกับระบบนี้นะครับ


วิธีที่ระบบ eJudge คำนวณคะแนน พี่จะยกตัวอย่างให้ว่า

หากน้องทำได้เพียง 9 ใน 10 testcase ได้ถูกต้อง และคะแนนต่อข้อ = 100 คะแนน และระดับความยาก = 5 และ ทำคุณภาพ code ระดับไม่มีที่ติ

|Testcase Score|Difficulty|Perfect Bonus score|Quality|Total|
|:------------:|:----------:|:-------------------:|:-------:|:-----:|
|(9/10) x 100  |x5        |100 x 5 x 0        |100%   |90 x 5 x 1 + 0 = 450|


หากน้องทำได้ 10 ใน 10 testcase ได้ถูกต้อง และคะแนนต่อข้อ = 100 คะแนน
และระดับความยาก = 5 และ ทำคุณภาพ code ระดับไม่มีที่ติ

|Testcase Score|Difficulty|Perfect Bonus score|Quality|Total|
|:------------:|:--------:|:-----------------:|:-----:|:---:|
|(10/10) x 100 |x5        |100 x 5 x 2        |100%   |100 x 5 x 1 + 500 = 1000|

> เห็นความแตกต่างนั้นมั้ยเอ่ย? 450 กับ 1000 คะแนน มันต่างกันมากเลยนะครับ
<br>

* **Testcase** คือ กรณีที่นำมาทดสอบ
* **Difficulty** คือ ระดับความยากของโจทย์
* **Perfect Bonus** คือ คะแนน Bonus เมื่อทำถูกทุก Testcase
* **Quality** คือ ความเป็นระเบียบของ Code
* **Total** คือ คะแนนรวมทั้งหมด

> ซึ่ง **Testcase, คะแนน หรือระดับความยาก** จะขึ้นอยู่กับผู้ออกโจทย์ โจทย์บอกข้ออาจมี 1000 คะแนนก็ได้


# Why Python?
![prepro logo](README/python-logo.png)
น้อง ๆ อาจจะไม่เข้าใจ ว่าทำไมเราต้องมาเรียน Python ด้วย ทำไมไม่เรียน C/Java ก่อน หรือ ไม่เรียน Ruby หรือ Swift ก่อน เพื่อเป็นการเรียนวิธีคิด พี่อยากจะบอกข้อดีของ Python ให้น้องฟังครับ

- **Speed** - น้องจะสามารถเขียนภาษานี้ได้เร็ว เพราะเป็นภาษา High Level

- **Integrations** - ระบบต่าง ๆ นั้นรองรับภาษา Python ทั้งหมด หากไม่รองรับ ก็สามารถใช้ Library เพื่อให้มันรองรับได้

- **Compatibility** - ใช้ได้กับทุกแพลตฟอร์มหลัก ๆ เช่น Windows และ UNIX (MacOS & Linux Distribution & Android)

> "Python is easy to learn and use, but powerful enough to tackle even the most difficult problems. It integrates well with existing IT infrastructure, and is very platform independent." - Continuum

# เนื้อหาการเรียนรอบ Online

> ## References
>
> ![thinkpython2e](README/think-python.jpg)
>
> Python Organizations (Document หลักของ Python) <br>
> https://docs.python.org/3/
>
> Think Python 2e (หนังสือเดียวที่เอาเข้าห้องสอบได้) <br>
> http://greenteapress.com/thinkpython2/thinkpython2.pdf
>
> Python Tutor (Python Cloud Debugger ทำงานทีละบรรทัด) <br>
> http://www.pythontutor.com
>

---
# การเตรียมตัวก่อน Onsite

## เรียน Onsite
การเรียน Onsite นี้จะแตกต่างกับรอบ Online ในระดับหนึ่ง เพราะจะเป็นการใช้เครื่องมือที่หลากหลายขึ้น (หรือในท่าที่ยากขึ้น) ต่างจากรอบ Online ที่พี่ ๆ ให้น้อง ๆ ได้ฝึกวาง Algorithm ให้เป็น และใช้เครื่องมือได้

## มา Onsite กันเถอะ

การเรียน Onsite จะเรียนทั้งหมด 4 Week จันทร์ - ศุกร์ เริ่ม วันที่ 10 มิถุนายน ถึง 5 กรกฎาคม 2019 ซึ่งการเรียน Onsite นั้นจัดขึ้นที่คณะเทคโนโลยีสารสนเทศ

การเรียน Onsite ให้ใส่ชุดธรรมดาสุภาพเรียบร้อย
* เสือยืดหรือเสื้อที่มันสุภาพ ๆ
* กางเกงขายาว
* รองเท้าผ้าใบ

>โดยหากมีข้อสงสัย หรือ ต้องการความช่วยเหลือ ติดต่อพี่ ๆ ได้เลยนะครับ

## การเดินทาง


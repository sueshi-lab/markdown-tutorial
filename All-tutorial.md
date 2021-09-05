# 1. Headings

เราจะใช้ `#` สำหรับทำ Headings ทั้ง 6 แบบ โดยเพิ่มจำนวน `#` ตามเลเวล Heading ที่เราต้องการได้เล้ย !

### :round_pushpin: ตัวอย่างที่ 1.1

```
# BorntoDev Heading 1
## BorntoDev Heading 2
### BorntoDev Heading 3
#### BorntoDev Heading 4
##### BorntoDev Heading 5
###### BorntoDev Heading 6
```

### :point_right: ผลลัพธ์ที่ได้

# BorntoDev Heading 1
## BorntoDev Heading 2
### BorntoDev Heading 3
#### BorntoDev Heading 4
##### BorntoDev Heading 5
###### BorntoDev Heading 6

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 1.2

นอกจากแบบตัวอย่างที่ 1.1 เรายังใช้ `===` และ `---` เพื่อแบ่งเลเวล Heading ได้เหมือนกัน

```
BorntoDev Heading 1
===
BorntoDev Heading 2
---
```

### :point_right: ผลลัพธ์ที่ได้

BorntoDev Heading 1
===
BorntoDev Heading 2
---

จะเห็นเลยว่า ผลลัพธ์เหมือนกับการใช้ `#` เลย
> ```
> # BorntoDev Heading 1
> ## BorntoDev Heading 2
> ```

:wavy_dash:

# 2. Paragraphs (New Line)

อยากขึ้นบรรทัดใหม่ ทำยังไงดีน้า?

### :round_pushpin: ตัวอย่างที่ 2.1

```
คุณเห็นด้วยไหม?
สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"
```
### :point_right: ผลลัพธ์ที่ได้

คุณเห็นด้วยไหม?
สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 2.2 (Hard Break)

จากตัวอย่างที่ 2.1 จะเห็นได้ว่า ตอนแสดงผล ข้อความดันกลายเป็นบรรทัดเดียวกัน ซึ่งถ้าเราต้องการให้เว้นบรรทัดให้ข้อความ เราจะต้องเคาะเว้นลงมาเป็นบรรทัดเปล่า 1 บรรทัดซะก่อน เรียกว่า **Hard Break** (เปรียบเหมือนการใช้ `Enter` นั่นเอง)

```
คุณเห็นด้วยไหม?

สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"
```
### :point_right: ผลลัพธ์ที่ได้

คุณเห็นด้วยไหม?

สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"  

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 2.3 (Soft Break)

อีกวิธีที่ใช้ขึ้นบรรทัดใหม่ได้ ก็คือเคาะเว้นวรรค 2 ครั้ง หลังบรรทัดที่ต้องการให้ขึ้นบรรทัดใหม่ ซึ่งแบบนี้เรียกว่า **Soft Break** (เปรียบเหมือนการใช้ `Shift+Enter` นั่นเอง) เช่น 

```
คุณเห็นด้วยไหม?
สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"
```

(ในตัวอย่างอาจจะไม่เห็น แต่จริง ๆ แล้ว เราเคาะ Space 2 ครั้ง หลังคำว่า "คุณเห็นด้วยไหม?" แบบข้างล่างนี้ด้วยนะ!)
> คุณเห็นด้วยไหม? `·` `·`  
> สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"

### :point_right: ผลลัพธ์ที่ได้

คุณเห็นด้วยไหม?  
สิ่งที่สำคัญกว่าการเขียนโค้ดคือ "การอ่านโค้ด"

:wavy_dash:

# 3. Horizontal Line

นอกจาก `---` จะใช้แบ่งเลเวล Heading ได้แล้ว ยังใช้สร้างเส้นคั่นแนวนอนได้อีกด้วย

### :round_pushpin: ตัวอย่างที่ 3.1

```
---
```
### :point_right: ผลลัพธ์ที่ได้

---

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 3.2

อ๊ะ ๆ แต่ว่านะ  
ถ้าเหนือเส้นคั่นมีข้อความล่ะก็ เราต้องเว้นบรรทัดลงมาก่อนนะ เส้นคั่นถึงจะแสดง ไม่อย่างนั้น `---` จะมองว่าข้อความข้างบนเป็น Heading แทน

```
อยากได้เส้นคั่นอะ
ก็บอกว่าอยากได้เส้นคั่นไง!
---
```

### :point_right: ผลลัพธ์ที่ได้

อยากได้เส้นคั่นอะ
ก็บอกว่าอยากได้เส้นคั่นไง!
---

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 3.3
เราจะแก้ปัญหาจากตัวอย่างที่ 3.2 ด้วยการเว้นบรรทัด!

```
อยากได้เส้นคั่นอะ
ก็บอกว่าอยากได้เส้นคั่นไง!

---
```

### :point_right: ผลลัพธ์ที่ได้

อยากได้เส้นคั่นอะ
ก็บอกว่าอยากได้เส้นคั่นไง!

---

:wavy_dash:

# 4. Text Styles
มาดูวิธีจัดการกับข้อความดีกว่า เราจะทำตัวเอียงและตัวหนา โดยใช้ `_` หรือ `*` ครอบข้อความที่เราต้องการให้เอียง และใช้ `__` หรือ `**` ครอบข้อความที่เราต้องการให้หนา

## Italics and Bold

### :round_pushpin: ตัวอย่างที่ 4.1

```
นี่คือ _ตัวเอียง_

นี่คือ __ตัวหนา__

นี่ก็*ตัวเอียง*เหมือนกัน

นี่ก็**ตัวหนา**เหมือนกัน
```

### :point_right: ผลลัพธ์ที่ได้

นี่คือ _ตัวเอียง_

นี่คือ __ตัวหนา__

นี่ก็*ตัวเอียง*เหมือนกัน

นี่ก็**ตัวหนา**เหมือนกัน

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 4.2

ลองใช้แบบผสมกันบ้าง ไหนดูซิว่าเป็นยังไง

```
มี**ตัวหนา**กับ*ตัวเอียง*บรรทัดเดียวกัน

มี**ตัวหนา**กับ _ตัวเอียง_ บรรทัดเดียวกัน

_มี **ตัวหนา** ในบรรทัดที่ทุกตัวอักษรเอียง_

**มี _ตัวเอียง_ ในบรรทัดที่ทุกตัวอักษรหนา**
```

### :point_right: ผลลัพธ์ที่ได้

มี**ตัวหนา**กับ *ตัวเอียง* บรรทัดเดียวกัน

มี**ตัวหนา**กับ _ตัวเอียง_ บรรทัดเดียวกัน

_มี **ตัวหนา** ในบรรทัดที่ทุกตัวอักษรเอียง_

**มี _ตัวเอียง_ ในบรรทัดที่ทุกตัวอักษรหนา**

:wavy_dash:

### :bulb: จุดสังเกต

ถ้าเราใช้ `_` หรือ `__` เราจะต้องเว้นวรรคข้างหน้าและข้างหลังของเครื่องหมาย `_` เพื่อให้ข้อความเป็นตัวเอียง ไม่อย่างนั้น `_` จะถูกมองว่าเป็นส่วนหนึ่งของข้อความ

แล้วเราอยากได้ทั้งตัวหนาและตัวเอียงพร้อมกันล่ะ?

### :round_pushpin: ตัวอย่างที่ 4.3

```
เป็นทั้ง ***ตัวหนาและตัวเอียง*** ในคำเดียวกัน 1

เป็นทั้ง ___ตัวหนาและตัวเอียง___ ในคำเดียวกัน 2

เป็นทั้ง **_ตัวหนาและตัวเอียง_** ในคำเดียวกัน 3
```

### :point_right: ผลลัพธ์ที่ได้

เป็นทั้ง ***ตัวหนาและตัวเอียง*** ในคำเดียวกัน 1

เป็นทั้ง ___ตัวหนาและตัวเอียง___ ในคำเดียวกัน 2

เป็นทั้ง **_ตัวหนาและตัวเอียง_** ในคำเดียวกัน 3

:wavy_dash:

## Strikethrough

เราสามารถขีดค่าข้อความที่เราต้องการด้วยการใช้ `~~` ครอบข้อความที่ต้องการ
### :round_pushpin: ตัวอย่างที่ 4.4

```
อยากขีดค่า~~ข้อความ~~นี้
```

### :point_right: ผลลัพธ์ที่ได้


อยากขีดค่า~~ข้อความ~~นี้

:wavy_dash:

# 5. Links

เราจะใช้ `[ ]` แสดงข้อความที่เราต้องการ คู่กับกับใส่ลิงก์ในวงเล็บ `( )` เพื่อทำการลิงก์ พูดงี้อาจจะนึกไม่ออก ไปดูตัวอย่างดีกว่า

### :round_pushpin: ตัวอย่างที่ 5.1

```
ติดตาม BorntoDev ได้ที่ [Facebook](https://www.facebook.com/borntodev)
```

### :point_right: ผลลัพธ์ที่ได้

ติดตาม BorntoDev ได้ที่ [Facebook](https://www.facebook.com/borntodev)

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 5.2
บางครั้ง ถ้าข้อความในเอกสารเราเยอะมาก การลิงก์แบบตัวอย่าง 5.1 อาจจะทำให้เกิดความสับสน ดังนั้น จึงขอเสนอการลิงก์แบบตัวอย่างข้างนี้เล้ย!

```
ติดตาม BorntoDev ได้ที่ [Facebook] | [YouTube] | [Instagram]

[Facebook]: https://www.facebook.com/borntodev
[YouTube]: https://www.youtube.com/c/BorntodevTH
[Instagram]: https://www.instagram.com/borntodev
```

### :point_right: ผลลัพธ์ที่ได้

ติดตาม BorntoDev ได้ที่ [Facebook] | [YouTube] | [Instagram]

[Facebook]: https://www.facebook.com/borntodev
[YouTube]: https://www.youtube.com/c/BorntodevTH
[Instagram]: https://www.instagram.com/borntodev

:wavy_dash:

# 6. Images

การแทรกรูปภาพแบบฉบับ Markdown จะใช้ Syntax คล้ายกับ Links เลย แต่เพิ่มเครื่องหมายตกใจ `!` ไปข้างหน้าแบบนี้ `![ ]( )` โดยเราอาจจะใช้วิธีการแทรกรูปได้ดังนี้

### :round_pushpin: ตัวอย่างที่ 6.1

```
![Logo](https://www.google.co.th/logos/doodles/2021/doodle-champion-island-games-september-05-6753651837109292-s.png)
```

### :point_right: ผลลัพธ์ที่ได้

![Logo](https://www.google.co.th/logos/doodles/2021/doodle-champion-island-games-september-05-6753651837109292-s.png)

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 6.2

```
![Logo]

[Logo]: https://www.google.co.th/logos/doodles/2021/doodle-champion-island-games-september-05-6753651837109292-s.png
```

### :point_right: ผลลัพธ์ที่ได้
![Logo]

[Logo]: https://www.google.co.th/logos/doodles/2021/doodle-champion-island-games-september-05-6753651837109292-s.png

# 7. Blockquotes

ไปต่อกันเลย ด้วยการทำ Quote เก๋ ๆ เพียงแค่ใช้ `>` หน้าข้อความที่ต้องการเท่านั้น

### :round_pushpin: ตัวอย่างที่ 7.1
```
รู้หรือไม่?

> ไก่กับไข่อะไรเกิดก่อนกัน
```

### :point_right: ผลลัพธ์ที่ได้

รู้หรือไม่?

> ไก่กับไข่อะไรเกิดก่อนกัน

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 7.2

```
รู้หรือไม่?

> ไก่กับไข่อะไรเกิดก่อนกัน
>
> ก็ต้องไก่สิ!

> ไม่ใช่ไข่เหรอ?

> แต่งานวิจัยเขาบอกว่าไก่นะ
```

### :point_right: ผลลัพธ์ที่ได้

รู้หรือไม่?

> ไก่กับไข่อะไรเกิดก่อนกัน
>
> ก็ต้องไก่สิ!

> ไม่ใช่ไข่เหรอ?

> แต่งานวิจัยเขาบอกว่าไก่นะ

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 7.3

```
รู้หรือไม่?

> ไก่กับไข่อะไรเกิดก่อนกัน
> > ก็ต้องไก่สิ!
> > > ไม่ใช่ไข่เหรอ?
> > > > แต่งานวิจัยเขาบอกว่าไก่นะ
```

### :point_right: ผลลัพธ์ที่ได้

รู้หรือไม่?

> ไก่กับไข่อะไรเกิดก่อนกัน
> > ก็ต้องไก่สิ!
> > > ไม่ใช่ไข่เหรอ?
> > > > แต่งานวิจัยเขาบอกว่าไก่นะ

(จบเรื่องนี้เถอะ)

:wavy_dash:

# 8. Lists

## Unordered List

การทำ Unordered List ทำได้หลายแบบมาก ๆ 

### :round_pushpin: ตัวอย่างที่ 8.1 ( * )

```
* มะเขือเทศ
* สับปะรด 
```

### :point_right: ผลลัพธ์ที่ได้

* มะเขือเทศ
* สับปะรด 

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 8.2 ( - )

```
- มะเขือเทศ
- สับปะรด 
```

### :point_right: ผลลัพธ์ที่ได้

- มะเขือเทศ
- สับปะรด 

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 8.3 ( + )

```
+ มะเขือเทศ
+ สับปะรด 
```

### :point_right: ผลลัพธ์ที่ได้

+ มะเขือเทศ
+ สับปะรด 

:wavy_dash:

## Ordered List

สำหรับ Ordered List เราจะใช้ตัวเลข `1.` `2.` `3.` รันรายการไปเรื่อย ๆ

### :round_pushpin: ตัวอย่างที่ 8.4

```
1. มะเขือเทศ
2. ผักกาด
3. องุ่น
4. สับปะรด 
```

### :point_right: ผลลัพธ์ที่ได้

1. มะเขือเทศ
2. ผักกาด
3. องุ่น
4. สับปะรด 

:wavy_dash:

## Nested List

ถ้าเราอยากสร้าง List ที่ซ้อนกัน ให้เราเคาะ Space เข้าไปแบบตัวอย่างข้างล่างนี้เลย

### :round_pushpin: ตัวอย่างที่ 8.5
```
* มะเขือเทศ
  * เนื้อสีแดง
  * มีคุณค่าทางอาหาร
    * วิตามินเอ
    * วิตามินซี
* สับปะรด
  * เนื้อสีเหลือง
  * มีผิวขรุขระ
```
### :point_right: ผลลัพธ์ที่ได้
* มะเขือเทศ
  * เนื้อสีแดง
  * มีคุณค่าทางอาหาร
    * วิตามินเอ
    * วิตามินซี
* สับปะรด
  * เนื้อสีเหลือง
  * มีผิวขรุขระ

:wavy_dash:

# 9. Code & Code Blocks

## Code

เราจะใช้เครื่องหมาย ` ครอบข้อความหรือโค้ดที่เราต้องการ เพื่อให้แสดงผลในรูปแบบของ Code

### :round_pushpin: ตัวอย่างที่ 9.1

```
แสดงข้อความบนภาษาไพธอน `print("Hello World")`
```

### :point_right: ผลลัพธ์ที่ได้

แสดงข้อความบนภาษาไพธอน `print("Hello World")`

:wavy_dash:

## Code Blocks

ถ้าต้องการให้ข้อความหรือโค้ดอยู่ในลักษณะ Code Block เราจะใช้เครื่องหมาย ``` ครอบข้อความที่ต้องการ

### :round_pushpin: ตัวอย่างที่ 9.2

``````
```
print("Hello World")  
```  
``````

### :point_right: ผลลัพธ์ที่ได้

```
print("Hello World")
```

:wavy_dash:


### :round_pushpin: ตัวอย่างที่ 9.3

หรือเพิ่มความเท่ขึ้นไปอีกด้วยการระบุภาษาของโค้ด ก็ระบุภาษาหลังเครื่องหมาย ``` แบบตัวอย่างข้างล่างนี้เลย

``````
```python
print("Hello World")  
```  

```java
public static void main(String args[]) {
        System.out.println("Hello, World!");
}
```
``````

### :point_right: ผลลัพธ์ที่ได้

```python
print("Hello World")
```

```java
public static void main(String args[]) {
        System.out.println("Hello, World!");
}
```

:wavy_dash:

# 10. Task Lists

สำหรับ Task List เราจะใช้ `- [x]` ใช้หรับ Checked ที่ Task นั้น และใช้ `- [ ]` สำหรับ Task ที่ไม่ได้ถูก Checked

(Task List รองรับแค่บางเว็บไซต์/แอปพลิเคชันเท่านั้น เช่น GitHub)

### :round_pushpin: ตัวอย่างที่ 10.1

```
- [x] Feature A
- [ ] Feature B
- [ ] Feature C
```

### :point_right: ผลลัพธ์ที่ได้

- [x] Feature A
- [ ] Feature B
- [ ] Feature C

:wavy_dash:

# 11. Tables

การทำตารางใน Markdown อาจจะต้องใช้จินตนาการนิดหน่อย โดยใช้เราคิดว่า `|` คือเส้นตารางแนวตั้ง และ `---` คือเส้นคั่นแนวนอนของหัวตาราง ไปดูตัวอย่างกันดีกว่า

(Tables รองรับแค่บางเว็บไซต์/แอปพลิเคชันเท่านั้น เช่น GitHub)

### :round_pushpin: ตัวอย่างที่ 11.1

```
#### ช่องทางติดตาม BorntoDev

| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| ---- | ---- | ---- |
| 1 | Facebook | https://www.facebook.com/borntodev |
| 10 | YouTube | https://www.youtube.com/c/BorntodevTH |
| 100 | Instagram | https://www.instagram.com/borntodev |
```

### :point_right: ผลลัพธ์ที่ได้

#### ช่องทางติดตาม BorntoDev

| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| ---- | ---- | ---- |
| 1 | Facebook | https://www.facebook.com/borntodev |
| 10 | YouTube | https://www.youtube.com/c/BorntodevTH |
| 100 | Instagram | https://www.instagram.com/borntodev |

:wavy_dash:

### :round_pushpin: ตัวอย่างที่ 11.2

นอกจากนี้ เรายังสามารถจัดชิดซ้าย ชิดขวา กึ่งกลางให้กับ Content ในตารางได้

โดยในส่วนของเส้นคั่นหัวตาราง เราจะใช้ `:--` จัดชิดซ้าย ใช้ `:--:` จัดกึ่งกลาง และใช้ `--:` จัดชิดขวา

```
#### ช่องทางติดตาม BorntoDev

| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| :---- | :----: | ----: |
| 1 | Facebook | https://www.facebook.com/borntodev |
| 10 | YouTube | https://www.youtube.com/c/BorntodevTH |
| 100 | Instagram | https://www.instagram.com/borntodev |
```

### :point_right: ผลลัพธ์ที่ได้

#### ช่องทางติดตาม BorntoDev

| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| :---- | :----: | ----: |
| 1 | Facebook | https://www.facebook.com/borntodev |
| 10 | YouTube | https://www.youtube.com/c/BorntodevTH |
| 100 | Instagram | https://www.instagram.com/borntodev |

:wavy_dash:

# 12. Emojis

นอกจากความสามารถต่าง ๆ ที่เราพูดไปก่อนหน้านี้ Markdown ยังสามารถแทรกอิโมจิได้อีกด้วย เช่น

### :round_pushpin: ตัวอย่างที่ 12.1

```
BorntoDev :t-rex: | Sunflower :sunflower: | Tomato :tomato:
```

### :point_right: ผลลัพธ์ที่ได้

BorntoDev :t-rex: | Sunflower :sunflower: | Tomato :tomato:

:wavy_dash:

--- 
Emoji ต่าง ๆ ส่องเพิ่มเติมได้ที่ https://www.webfx.com/tools/emoji-cheat-sheet/ หรือ https://emojipedia.org/  
(การแสดงผลของอิโมจิขึ้นอยู่กับเว็บไซต์/แอปพลิเคชัน/แพลตฟอร์มที่เราใช้งานด้วยนะ :sparkles:)

ใครที่อยากรู้ Syntax ของ Markdown บน Github สามารถอ่านเพิ่มเติมได้ที่ [GitHub Docs](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

:wavy_dash:

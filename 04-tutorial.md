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
| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| ---- | ---- | ---- |
| 1 | Facebook | https://www.facebook.com/borntodev |
| 10 | YouTube | https://www.youtube.com/c/BorntodevTH |
| 100 | Instagram | https://www.instagram.com/borntodev |
```

### :point_right: ผลลัพธ์ที่ได้

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
| ลำดับที่ | ช่องทางติดตาม | ลิงก์ของแต่ละช่องทาง |
| :---- | :----: | ----: |
| 1 | Facebook | https://www.facebook.com/borntodev |
| 10 | YouTube | https://www.youtube.com/c/BorntodevTH |
| 100 | Instagram | https://www.instagram.com/borntodev |
```

### :point_right: ผลลัพธ์ที่ได้

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

สำหรับ Emoji ต่าง ๆ ส่องเพิ่มเติมได้ที่ https://www.webfx.com/tools/emoji-cheat-sheet/ หรือ https://emojipedia.org/

(การแสดงผลของอิโมจิขึ้นอยู่กับเว็บไซต์/แอปพลิเคชัน/แพลตฟอร์มที่เราใช้งานด้วยนะ :sparkles:)

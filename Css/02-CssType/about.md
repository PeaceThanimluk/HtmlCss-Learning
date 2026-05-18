#   วิธีการเขียนcssจะมี3วิธี

## 1.Inline stlye
จะเขียนอยู่ในElement ของhtml

```html
<h1 stlye="color: red;">Hello</h1>
```

## 2.Internal stlye
จะสร้าง tag style อยู่ในส่วนของ tag head ขึ้นมาแล้วเขียนcssในtag

```html
<head>

    <style>
        p{
            color: red;
        }
    </style>

</head>
```

## 3.External style(แนะนำที่สุด)
จะสร้างไฟล์cssแยกมาแล้วเขียนในไฟล์ 
**ต้องมีการlink file ในส่วนของhtmlก่อนถึงจะทำงานได้**
**ตำแหน่ง link rel ต้องอยู่ในส่วนของ head**

```html
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="ชื่อไฟล์หรือตำแหน่งไฟล์">
```
หลังจากนั้นก็สามารถEditในCssได้เลย
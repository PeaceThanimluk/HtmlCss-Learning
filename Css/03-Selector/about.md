# Selector
คือการเรียกใช้งานส่วนของ element , id , class ของ html

## Element Selector
คือเลือกส่วนของ element มา เช่น
ทุกตัวที่เป็น elementนั้น จะมีการเปลี่ยนแปลงเหมือนกันหมด

**HTML**
```html
<p>Hello</p>
<h1>head</h1>

<body>
    
</body>
```

**CSS**

```css
p{
    color: red;
}

h1{
    color: lime;
}

body{
    background-color: black;
}
```

## Class Selector
คือเลือกส่วนClassมาใช้งาน
- วิธีเรียกคือ .ชื่อclass

**HTML**
```html
<p class="Ju">ba</p>

<div class="Test"></div>
```

**CSS**
```css
.Ju{
    color: red;
}

.Test{
    background-color: black;
}
```

## Id Selector
คือเลือกส่วน id มาใช้งาน
ปกติใช้กับสิ่งที่มีแค่อันเดียวในหน้าเว็บ เช่น:

- Navbar หลัก
- Header
- Footer
- Modal
- ปุ่มพิเศษ
- Section เฉพาะ

หรือใช้กับ javascript

***วิธีเรียกใช้คือ #ชื่อid***

**HTML**
```html
<button id="myButton">Start</button>
```

**CSS**
```css
#myButton{
    color: red;
}
```

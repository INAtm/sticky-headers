
# Липкие панели
Липкие панели на js

![example image](https://lh4.googleusercontent.com/ibvXAw3wOpL8Fg9p5QJin-PnSb09QK8fmjhVJrJrfQjo-kbB06dYzi8CuP-eFCSug8C-Le1I4a3UQlQ=w1366-h661 "An exemplary image")
![example image](https://drive.google.com/open?id=0Bx_y-E2kyL4Db1FvNXB5bTQ0ZWc "An exemplary image")
# Примеры
### demo1.html
### demo2.html

# Установка
Подключить скрипт из assets/scripts/stiky.js

```html
<script src="assets/scripts/stiky.js"></script>
```

# Использование

html
```html
<div data-he="one">Test header</div>
<div data-co="one">Test content</div>
<div data-he="two">Test header</div>
<div data-co="two">Test content</div>
```

javaScript
```javascript
var options = {
  header: 'data-he', // Липкие панели
  content: 'data-co', // Контент
  activeClass: 'active-class', // Активный класс, который добавится липкой панели
  tspace: true // Добавлять ли высоту липкой панели к контенту (padding-top)
};
var sticky = new sinaz(options);
```

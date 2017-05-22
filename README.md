
# Липкие панели
Липкие панели на js

![example image](https://drive.google.com/open?id=0Bx_y-E2kyL4DUGhpb2ZBNzd4TU0 "An exemplary image")

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

# Spring-Sunset-ttk-theme  | Spring-Sunset ttk Тема
 

![Light screenshot](https://github.com/blyamur/Spring-Sunset-ttk-theme/blob/main/Light%20Screenshot.png)
######

## How to use? Как использовать
Using a theme should be very simple, so customizing the theme is handled by a separate tcl script.
This way, no matter what theme you want to use, you only need to import one file.

Использование темы должно быть очень простым, поэтому настройка темы обрабатывается отдельным скриптом tcl.
Таким образом, независимо от того,  какую тему вы хотите использовать, вам нужно импортировать только один файл. 

```python
# Just simply import the spring-sunset.tcl file 
# Просто импортируйте файл spring-sunset.tcl
widget.tk.call("source", "spring-sunset.tcl")

# Then set the theme you want with the set_theme procedure
# Затем установите желаемую тему с помощью процедуры set_theme
widget.tk.call("set_theme", "light") 
```

![Light screenshot](https://github.com/blyamur/Spring-Sunset-ttk-theme/blob/main/Example%20Screenshot.png)


## Bugs | Глюки
- Tk isn't really good at displaying `png` images, so if your program is laggy with the theme, please check out the [gif-based branch!](https://github.com/rdbende/Sun-Valley-ttk-theme/tree/gif-based/)
- When you change the theme, the window resizes. This is a quite strange bug that applies to all ttk themes. 
- Когда вы меняете тему, размер окна меняется. Это довольно странная ошибка, которая распространяется на все темы ttk.

## Examples | Примеры
Светлая тема | Light theme:  [Spring-Noon-ttk-theme](https://github.com/blyamur/Spring-Noon-ttk-theme/).

Examples | Примеры: [Sun-Valley-ttk-examples](https://github.com/rdbende/Sun-Valley-ttk-examples).  [rdbende](https://github.com/rdbende/Sun-Valley-ttk-theme)



*If You want to help me, you can buy me a cup of cup of coffee ( [yoomoney](https://yoomoney.ru/to/41001158104834) or [PayPal](https://paypal.me/enkonu) or [ko-fi](https://ko-fi.com/W7W460SQ3) )*

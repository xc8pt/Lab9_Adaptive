# Лабораторная работа №9. Адаптивная верстка: Медиа-запросы
Цель работы: Изучить принципы адаптивной верстки и медиа-запросов. В конце
создать адаптивную страницу портфолио, которая корректно отображается на всех
устройствах.
[] Поспать
[] Поесть
[x] Выполнить лабу по ИСРПО

## Что мы делали в данной лабораторной работе?

### **Медиа-запросы и адаптивность**

Пример:
```css
@media (max-width: 1024px) {
    .container {
        grid-template-columns: repeat(4, 1fr);
    }
}

@media (min-width: 768px) and (max-width: 1023px) {
    .container {
        grid-template-columns: repeat(2, 1fr);
    }
}
```
### Стандартные **breakpoints** (контрольные точки)

Пример: 
```css
.container {
    padding: 10px;
}

@media (min-sidth: 576px) {
    .container {
        padding: 15px;
    }
}

@media (min-width: 768px) {
    .container {
        padding: 20px;
    }
}

@media (min-width: 992px) {
    .container {
        padding: 25px;
    }
}

@media (min-width: 1200px) {
    .container {
        padding: 30px;
    }
}
```

### **Mobile First vs Desktop First**
Mobile First — начинаем с мобильных стилей, затем расширяем для больших
экранов.

Desktop First — начинаем с десктопных стилей, затем адаптируем для маленьких
экранов.

### Создали сайт и протестировали на нем разные разрешения.
[!Скриншот1](img/responsiveDesktopLab9_AbdulinRR.png)
[!Скриншот2](img/responsiveMobileLab9_AbdulinRR.png)
[!Скриншот3](img/responsiveTabletLab9_AbdulinRR.png)


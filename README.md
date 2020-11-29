# Структура

```
toxin/
│
├── dist/                # Итоговая сборка
├── src/                 # Папка разработки
│
└── package.json
```

Папка разработки:
```
src/
│
├── pages/     # Страницы отображаемые на компьютере
│   ├── cards.pug                                         # страница   UI-KIT
│   ├── cards.scss                                        # страница   UI-KIT
│   ├── colors_and_type_ui.pug                            # страница  UI-KIT
│   ├── colors_and_type_ui.scss                           # страница  UI-KIT
│   ├── form_elements.pug                                  # страница  UI-KIT
│   ├── form_elements.scss                                 # страница  UI-KIT
│   ├── index.pug                                      # главная страница сайта
│   ├── index.scss                                     # главная страница сайта
│   └──  # файлы .svg здесь находиться не дложны, но пока без этого не работает 
│  
├── mobile/       # Страницы отображаемые на мобильных устройствах
│   ├── 
│   └── 
│
├── components/         # Компоненты по БЭМ
│   │
│   ├── / room_details  # комфорт, удобств, уют номера (form_elements 1столбец, низ)
│   │    
│   │

│   └── /         # 
│       ├── /
│       ├── /
│       └── /
│
├── fonts/  # Шрифты (папка со шрифрами в форматах .ttf, .wof, .svg, .eot )
│
└── scss/            # файлы scss общие для проекта
    ├── fonts.css        #  шрифты 
    ├── main.css         #  главный файл стилей
    ├── normalize.css    #  сброс стилей
    └── variables.scss     #  переменные scss для смены стиля проекта


```
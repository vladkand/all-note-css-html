# /\* _ для ссылок aria-label _/

# - button - по умолчаию НЕ наследует шрифт

    в modern-normalise-> это исправляется!!!

# - для button

    убираем:
     padding: 0;
     border: none;

## modern-normalise:

    https://cdnjs.com/
    https://cdnjs.com/libraries/modern-normalize
    или
    https://github.com/sindresorhus/modern-normalize
    https://cdnjs.com/libraries/modern-normalize

##### feachure

        button{
            cursor: pointer;
        }

# Переменные лучше задавать для отдельных сущностей

    т.е.
         --footer-color-txt: #fff;
         --header-color-txt: #fff;
         --section-bg-color: teal;
         --logo-color-txt: teal;

# sharp-config

## Script sharp для билда webpack 5

### поставленные задачи
+ оптимизация (сжатие)
    - без потерь
    - более высокое сжатие
+ ресайзинг (мобайл, таблет, десктоп, ретина)
+ генерация современных форматов
    - webp
+ создание плейсхолдеров

### импорт библиотеки
const sharp = require('sharp')

### использование
`sharp(input: string, options: object)`

> input может быть Buffer/Unit8Array, то есть содержать непосредственно данные изображения или содержать файловый путь к изображению
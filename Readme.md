## Ручные настройки
| №   | Plugin           | Description  |
| --- |-------------| -----:|
| 1.  | ![UTF-8]()                            | Editor->File Encodings |
| 2.  | ![Set version]()                       | Languages&Frameworks->PHP |
| 3.  | ![Set editor settings]()                            | Перевод каретки, версия пыхи, количество пробелов при табуляции, encoding |
| 4.  | [Symfony settings]()   | Languages&Frameworks->PHP->Symfony |

## Экспортируемые настройки

```shell
mv .editorconfig ~/projects/#CURRENT_PROJECT#/.editorconfig
```

### Открываем настройки
1. File->Settings (ctrl+alt+s);

#### Переходим в настройки стилей кода, по следующему пути: 
2. Editor->CodeStyle;

_Должна стоять галочка **"Enable Editor Config Support".**_
Если не стояла, то проставляем и нажимаем **Apply**

#### Переходим в настройки стилей кода, по следующему пути:

3. Editor->Inspections

- Напротив select Profile нажимаем шестеренку ![settings]( "settings") [Подсказка](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)
- В выпадающем меню, нажимаем export 
- Выбираем файл MicroService.xml
- Нажимаем Apply

### Нажимаем Ok


## Плагины

### Обязательные

| №   | Plugin           | Description  |
| --- |-------------| -----:|
| 1.  | [symfony-support](https://plugins.jetbrains.com/plugin/7219-symfony-support)                            | Symfony |
| 2.  | [env-files-support](https://plugins.jetbrains.com/plugin/9525--env-files-support)                       | Поддержка работы с .env |
| 3.  | [php-annotations](https://plugins.jetbrains.com/plugin/7320-php-annotations)                            | Подсказки в аннотациях |
| 4.  | [php-inspections-ea-extended](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)   | Php инспектор |

### По желанию

| №   | Plugin | Description  |
| --- |-------------| -----:|
| 1.  | [rainbow-brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) | Подсветка скобочек |

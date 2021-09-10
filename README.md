# **Var Mod**

![Var Mod](https://i.imgur.com/eP5FUcS.png)

## **Описание**

Various Modification (сокращённо Var Mod), также известный как TrashMachina или Ex Randomina, является первым и, пока что, единственным модом для Ex Machina, вносящим в ваш геймплей элемент случайности.

Для достижения подобного эффекта был написан специальный скрипт, который, в зависимости от его настроек, рандомизирует тот или иной геймплейный элемент.

Пока что скрипт сырой и находится в стадии бета-теста, но основные его функции прекрасно работают.

Огромная благодарность выражается товарищам [Seel](https://github.com/Zvetkov) и [ThePlain](https://github.com/ThePlain) за неоценимую помощь и частичное участие в разработке.

## **Установка**
**ВАЖНО!** Скрипт работает только на Windows 10 64bit.

Некоторые антивирусы могут распознать исполняемый файл как вредоносный. К сожалению, полностью исправить эту проблему невозможно.

Вот ссылка на [VirusTotal](https://www.virustotal.com/gui/file/1b29e82aa0ef6a28bf892d9995f0fd3809b3fe98ca397a03e0b416db067e70d5), где этот файл успешно прошёл проверку.

1. Скачайте последний релиз [отсюда](https://github.com/zatinu322/Var-Mod-Trash-Machina/releases).
2. **Обязательно** распакуйте архив в любую директорию.
3. Запустите исполняемый файл и следуйте инструкциям внутри него.

## **Настройка**
### 1. **Путь**
Сначала укажите корневую директорию с установленной игрой. По умолчанию в этом поле указана текущая директория исполняемого файла. Если вы распаковали архив непосредственно в директорию с игрой, которую собираетесь рандомизировать - этот шаг можно пропустить.

### 2. **Параметры рандомизации**
![Параметры рандомизации](https://i.imgur.com/AmkyK7j.png)
Затем выберите те опции, которые хотите рандомизировать. После этого **обязательно** нажмите на кнопку "Применить" справа внизу.

Для большего удобства опции разделены на категории. 

Красным цветом отмечены опции, которые в теории могут вызвать софтлок и сделать дальнейшее прохождение невозможным.

Синим цветом отмечены опции, которые рандомизируют игру на уровне внутренних lua-скриптов. Это означает, что каждый раз одна и та же катсцены и один и тот же игровой враг будет выглядеть по-другому.

_Автор не рекомендует одновременно рандомизировать модели окружения и текстуры окружения, так как это может вызвать определённые визуальные трудности._

**Сбросить Lua** - отменяет динамический рандом, если он до этого был вами включен.

**Режим дебага** - вывод в лог информации о каждом файле и каждой команде, которые участвуют в процессе рандомизации. Для обычного пользователя не нужна.

**ВНИМАНИЕ!** По техническим причинам функция рандомизации FOV для Community Remaster временно отключена.

### 3. **Версия игры**
Затем выберите версию игры. Пока что поддерживаются только лицензия Steam 1.02 и Community Remaster.

Если вы случайно выбрали не ту версию, в большинстве случаев рандомайзер обнаружит несоответсвие и сообщит вам, что вы не правы.
### 4. **Начните рандомизацию**
Нажмите на кнопку "Начать рандомизацию" и программа сделает всё, что нужно.

Если в процессе работы рандомайзера возникли ошибки, вы получите уведомление об этом.

Более подробно с возникшими проблемами вы можете ознакомиться в файле _randomizer.log_, который будет создан (или перезаписан, если вы запускаете рандомайзер не первый раз) в директории с программой.
## **Конфигурация**
В папке resources, необходимой для работы рандомайзера, находятся файлы формата *.yaml, которые служат его конфигом. В нём содержатся списки файлов по категориям в порядке, аналогичном их расположению в окне параметров рандомизации.

**ВАЖНО!** Настоятельно не рекомендую ничего в нём менять, если вы понятия не имеете, что такое YAML и как с ним работать.

## **Заключение**
Больше контента по Ex Machina вы можете найти здесь:
1. [Мой Discord](https://discord.gg/sPrGBP9aFd)
2. [Мой YouTube](https://www.youtube.com/user/rpggameland)
3. [Discord DEM](https://discord.gg/qKK2Efx)


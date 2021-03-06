# SunChat (Not relevant)
# SunChat :arrow_right: [lightChat](http://github.com/rTiRe/lightChat)

## Minecraft плагин на глобальный, локальный и мировой чат.

**Глобальный чат** - сообщения видны всем игрокам.

**Локальный чат** - сообщения видны лишь игрокам, которые находятся в заданном радиусе по `x` и `z` от отправителя.

**Мировой чат** - сообщения видны лишь игрокам, которые находятся в одном измерении(мире) с отправителем.

⠀

При первом запуске в папке `plugins` появится папка `SunChat` со стандартным конфигом. Вы редактируете конфиг под себя.
   
## Краткий курс по настройке конфига

Для форматирования текста используется конструкция   `&[код]`   . Например: `&5&lHello` выдаст нам фиолетовое `Hello` с жирным начертанием букв.
   
Для получения ника зашедшего/вышедшего игрока используется конструкция `%p`. Например: `Hello, %p` выдаст нам сообщение `Hello, [ник игрока]`.
   
### А теперь ближе к делу

В конфиге есть несколько строк и подстрок:

#### GlobalChat

⠀**ChatPrefix** - какой первый символ(ы) в сообщении будут говорить о том, что оно должно отправится в глобальный чат.

⠀**MessagePrefix** - тут вы пишите то, что будет выводится до сообщения.

⠀**MessageColor** - цвет сообщения.

#### LocalChat

⠀**MessagePrefix** - тут вы пишите то, что будет выводится до сообщения.

⠀**MessageColor** - цвет сообщения.

⠀**ChatDistantion** - радиус, находясь в котором игроки получат сообщение.

#### WorldChat

⠀**enable** - включен ли мировой чат. Может принимать лишь `true` - чат включен, либо любое другое значение - чат выключен. 

⠀**ChatPrefix** - какой первый символ(ы) в сообщении будут говорить о том, что оно должно отправится в мировой чат.

⠀**MessagePrefix** - тут вы пишите то, что будет выводится до сообщения.

⠀**MessageColor** - цвет сообщения.

#### reload

⠀**success** - сообщение, выводимое при успешной перезагрузке плагина.

⠀**noPermission** - сообщение, выводимое игроку при использовании, если у того нет права на использование команды.

Все строки могут иметь лишь 1 аргумент и этот самый аргумент пишется в `' '` сразу после двоеточия. Например: `MessageColor: '&f'`.

**Молодцы! Конфиг настроен под вас.**

## Commands

`/sсr` - перезагружает конфиг, дабы не перезагружать сервер или все плагины.

## Permissions

`sс.reload`

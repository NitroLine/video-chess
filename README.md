# GameRoulette

Это чат рулетка в который вы можете поиграть с собеседником в различные пошаговые игры

https://gameroulette.2tapp.cc


# Требования к проекту

- Возможность использовать камеру, микрофон и чат для общения с собеседником
- Возможность играть в игру, после окончания игры общающиеся могут сыграть еще раз или покинуть комнату и искать
  другого оппонента
- Точка расширения добавления новых игры
- 3 начальных игры

## Начальные игры
- Шахматы
- Крестики нолики
- Русская рулетка

## Описание интерфейса игры

- Два плеера расположенные вертикально
- Шахматная доска
- Кнопка найти нового соперника
- Селектор выбора девайсов

# Запуск

- `npm install`
- `npm run buld`
- Setup port in `.env` file 
- `npm start`

# Технологии

- PeerJS
- Socket.io
- Chess.js

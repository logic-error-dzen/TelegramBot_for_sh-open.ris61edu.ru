Бот позволяет получать оценки из электронного журнала в телеграм. Необходимо настроить cfg.json (инструкция в readme.txt) и запустить бота

Используемые модули: fake_useragent, requests, telebot, BeatifulSoup, json. Их необходимо установить через pip install

*** RUS/РУССКИЙ

--- Настройка

JSON файлы кроме cfg.json и role.json(по желанию) не трогаем.

В cfg.json прописываем {токен бота от botfather}, {id канала (бот проверяет подписку)}, {ваш ник в тг или номер телефона}, {ссылку на ваш тг канал, чтобы его могли найти}

В cfg.json находится статус юзеров. Пока это не доведено до ума. Статус new дает задержку 5 секунд при запросе, чего нет у new и admin. В планах сделать больший список ролей и добавить ограничения.

--- Запуск

Запуск - через main.py, один процесс. 
--- Команды

/start - очевидно
/pass - для прописки логина+пароля юзером
/zap - запрос

1.Заходим в botfather( https://t.me/BotFather )
1.1 Прописываем команду /newbot , регистрируем бота, копируем токен бота 

2. Заходим в файл prm.php ищем 7 строку, меняем токен "6702099625:AAFpwp5Nm8tD4iVUNLufkBYe-6Kr8oiABX8" на ваш
3. Заходим в файл connect.php, меняем данные от базы данных
4. Закидываем данные на хостинг, импортим файл "bdproverka.sql" в phpmyadmin и последнее что требуется - создать вебхук
5. Создаем вебхук
https://api.telegram.org/botТокенБота/setwebhook?url=путь до файла bot.php 
Пример - ( https://api.telegram.org/6702099625:AAFpwp5Nm8tD4iVUNLufkBYe-6Kr8oiABX8/setwebhook?url=domain.com/bot.php ) 

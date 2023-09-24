title: Discord bot
description: Бот для автоматической рассылки постов из группы ВК в Discord-канал.
category: Bots
icon: bx bx-message-detail
info: Ссылка на код бота
link: https://github.com/Nikitimba09/Discord-bot

###Бот, первое тз полученное мной в IT-клубе, начало моего пути.

Для бота использовал следующее:

VkApi для работы с АПИ ВК

from config import settings для безопасности лучше использовать скрытую информацию при публикации и развертывания 
сайтов.

from vk_api.bot_longpoll import VkBotLongPoll, VkBotEventType модули для получения информации о постах, типах и тп.

import requests Стандартная библиотека requests для запросов.

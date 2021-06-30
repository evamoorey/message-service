# Message service
Service for post and get messages from users on ASP .NET 5

Вообще в Swagger всё предельно ясно, но распишу запросы и тут.
senderId (receiverId) - это email прользователя!

User:
create-user (создание пользователя с аргументами: имя, емейл)
initialize-random (создание рандомного списка пользователей и сообщений)
get-users (получение списка пользователей. С двумя не обязательными аргументами из ТЗ)
{email} (получение пользователя по его емейл)

Message:
create-message (создание сообщения с аргументами: тема, текст сообщения, отправитель емейл, получатель емейл)
get-messages-senderid-receiverid (получение сообщений от одного пользователя другому. С аргументами: емейл отправителя, емейл получателя)
get-messages-senderid (получение сообщений от пользователя. С аргументом: емейл пользователя)
get-messages-receiverid (получение сообщений пользователя. Аргумент: емейл пользователя) 

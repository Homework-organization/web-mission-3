# Mission 3

## Part 1 and 2

[Link to video](https://share.vidyard.com/watch/KbHFJfDCZfh8iMyf3HRWGB?)
 
## Part 3

- Запрос 1	 
> Ответ: select "username" FROM "Users"

- Запрос 2	 
> Ответ: select "from", count(*) AS number_of_sent_messages FROM "Messages" GROUP BY "from"

- Запрос 3	 
> Ответ: select "to" AS username, count(*) AS number_of_received_messages FROM "Messages" GROUP BY "to" ORDER BY number_of_received_messages desc LIMIT 1

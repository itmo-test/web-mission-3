# Mission 3

## Part 0-2

[Link to video] https://drive.google.com/file/d/1VIB5MfKPLTjtqICOsmRe_OLtsD3PWulB/view?usp=sharing

## Part 3

- Запрос 1	 
**SELECT** username **FROM** users

- Запрос 2	 
**SELECT** users.username, **COUNT(*) AS** number_of_sent_messages 
**FROM** messages
**JOIN** users ON messages.from = users.id
**GROUP BY** users.username

- Запрос 3	 
**SELECT** users.username, **COUNT(*) AS** number_of_received_messages 
**FROM** messages
**JOIN** users **ON** messages.**TO** = users.id
**GROUP BY** users.username
**ORDER by** number_of_received_messages **DESC**
**LIMIT** 1

- Запрос 4	 
Я не  поняла, как это сделать

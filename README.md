# Решение задачи 1 (Клиент-серверное приложение).

**Условие задачи**
После выполнения этого задания вы научитесь создавать сервер, способный принимать подключения.  
А также клиента, который будет подключаться к подобному серверу.

Создайте сервер с использованием ServerSocket.   
При входящем соединении на сервер, примите его, прочитайте из него строку. Выведите её на экран вместе с номером порта, с которого это соединение пришло.

Вместе с этим в другом методе (это может быть другой класс со вторым main методом или отдельный поток) подключитесь к этому серверу и отправьте ему одну строку.
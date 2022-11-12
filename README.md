# Запуск скрипта
<code>/path/to/jmeter/jmeter -n -t /path/to/testtask.jmx/testtask.jmx -l /path/to/testtask.jmx/log-testtask.out</code>

В результате выполнения теста будут сформированы файлы log-testtask.out (лог теста) и results.csv в директории <code>/path/to/testtask.jmx/</code>

# Профиль нагрузки
startRps = 5

step = 5

stepCount = 2

stepDuration = 180

rampUpPeriod = 15

____


Получить токен гостя - 100%

Регистрация игрока - 10%

Авторизация игроком - 100%

Запросить данные профиля игрока - 70%

Запросить данные другого игрока - 30%

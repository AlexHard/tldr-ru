# killall

> Отправить сигнал всем процессам, имеющим указанное имя (точное совпадение).
> Все сигналы, за исключением SIGKILL и SIGSTOP могут быть перехвачены процессами для корректной остановки / иного поведения.

- Прервать процесс, используя SIGTERM сингал (по-умолчанию -- сигнал завершения):

`killall {{process_name}}`

- Список всех доступных сигналов (перефикс "SIG" не используется командой):

`killall --list`

- Интерактивный решим -- спрашивает разрешение перед отправкой сигнала:

`killall -i {{process_name}}`

- Прервать процесс, используя SIGINT (прервать) сингал, эквивалентный нажатию `Ctrl + C` в терминале:

`killall -INT {{process_name}}`

- Завершить процессы форсированно:

`killall -KILL {{process_name}}`

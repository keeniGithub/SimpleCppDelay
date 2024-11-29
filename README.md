# Простая библиотека для задержки в C++

---

### Подключение

- Переместите `delay.hpp` в папку с проектом
- Подключите библиотеку в файле:

```cpp
#include "delay.hpp"
```

### Функции

- Задержка в миллисекундах

```cpp
delayms(int msec);
```

- Задержка в секундах

```cpp
delaysc(int sec);
```

- Задержка в минутах

```cpp
delaymn(int min);
```

- Задержка в часах

```cpp
delayhr(int hour);
```

## Пример использования в `example.cpp`

```cpp
#include "delay.hpp"

int main()
{
    while (true)
    {
        printf("hello\n");
        delayms(500);
    }
}
```

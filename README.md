# Программное обеспечение для discord
![Фото разработчика](images.jfif "Селфи")
## Описание программы
ПО для приложения discord помогающее более вариативно настраивать активность в профиле и выбирать произвольные приложения.

### Примеры реализации

**Подключение и настройка статуса (`main.py`)**
Программа использует библиотеку `pypresence` для передачи кастомного статуса в клиент Discord:

```python
from pypresence import Presence
import time

CLIENT_ID = "123456789012345678"  # ID вашего приложения в Discord Developer Portal
RPC = Presence(CLIENT_ID)
RPC.connect()

# Установка кастомной активности
RPC.update(
    state="Выбирает произвольное ПО",
    details="Настройка профиля Discord",
    large_image="logo_main",
    large_text="Custom RPC v1.0",
    start=time.time()
)

print("Статус успешно обновлен! Нажмите Ctrl+C для выхода.")
while True:
    time.sleep(15)
```
#### Необходимые условия и установка

| Параметр / Этап | Требования и действия |
| :--- | :--- |
| **Язык программирования** | Python версии 3.8 или выше |
| **Операционная система** | Windows 10, 11 |
| **Шаг 1. Загрузка** | Скачайте архив с программой |
| **Шаг 2. Подготовка** | Распакуйте архив в удобную папку |
| **Шаг 3. Запуск** | Запустите файл `start.bat` и нажмите пробел |

##### Информация обо мне
* **Автор:** Никита Пермичев
* **Группа:** ИС24Б
* **Специальность:** Информационные системы и программирование
* **Почта для связи:** [nv.permichev45@gmail.com](mailto:nv.permichev45@gmail.com)
* **Мой профиль на GitHub:** [Перейти в профиль](https://github.com/nikitapermichev))
* **При поддержке:** [Перейти](https://encrypted-tbn0.gstatic.com/licensed-image?q=tbn:ANd9GcRv___tCO87l38diX3O8rmNIXiWHMJaMdMwmTWckHQZozHwUsWEGqvIxUhW21VUi_1gDrhpB6mf4XLSkf8WchVpAoFJVuAT&s=19)

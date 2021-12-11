# Предусловия
* Пользователь должен иметь аппаратную часть
* Пользователь должен установить мобильное приложение

# Постусловия
* Отображение значений параметров воды
* Отображение результата рекомендации употребления воды
* Отображение истории замеров
* Отображение статистики значений параметров воды за определённый период времени

# Сценарий
* Пользователь переводит аппаратную часть в рабочее состояние
* Пользователь запускает мобильное приложение
* Пользоваетль производит подключение мобильного устройства к аппаратной части посредством bluetooth-соеднинения
* Пользователь нажимает на кнопку "Произвести замер"
* Приложение получает значения параметров от аппаратной части
* Приложение отображает полученные значения параметров
* Пользователь нажимает на кнопку "Остановить замер"
* Приложение сравнивает полученные значения параметров с нормой
* Приложение отображает результат рекомендации
* Приложение добавляет полученные значения параметров и разультат рекомендации в БД
* Приложение отображает историю замеров
* Приложение отображает статистику значений параметров
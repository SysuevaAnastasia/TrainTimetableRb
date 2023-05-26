## Требования к проекту

Создать приложение «Расписание поездов»
* Данные о пользователе:
  * ID_пользователя  — ключ
  * Логин
  * Пароль
  * ID_pоль (обычный/админ) 
  
* Реализация поиска пользователем нужного поезда по любому из критериев (будут указаны ниже).
* Реализация просмотра пользователем расписания поездов, а также просмотра данных одного поезда.
* Реализация добавления пользователем нужного поезда в избранное.
* Реализация удаления пользователем поезда из избранного.

Дополнительно для администратора
* Реализация добавления администратором расписания для новых поездов.
* Реализация изменения администратором расписания для уже имеющихся поездов.
* Реализация удаления администратором расписания для поездов, которые перестали ходить.

Информация о поезде включает в себя:
  * Номер поезда
  * Место начала маршрута (откуда выезжает поезд)
  * Место завершения маршрута (куда приезжает поезд)
  
  ## База данных
  ![бд](https://user-images.githubusercontent.com/101638603/198398047-73e4dec3-a458-4501-bd78-bec8e1921f7a.png)

  Пояснение к расписанию:
   * Дата прибытия поезда на какую-то станцию
   * Дата отправления поезда с какой-то станции
   * Название станции
   * Номер поезда, который совершает маршрут

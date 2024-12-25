# Яблонская Евгения, Лабораторная работа 6, Установка корпоративной вики и системы управления задачами

## Введение
• Краткое описание целей и задач лабораторной работы.
Цель данной лабораторной работы — изучить процесс установки корпоративной вики и системы управления задачами (таск-трекера) на локальный сервер (ваш компьютер), оценить их основные возможности, особенности настройки и, опционально (что является очень желательным в реальных рабочих условиях), опробовать их интеграцию. Данное задание направлено на практическое освоение инструментов управления знаниями и проектами, которые используются в корпоративной среде.
• Список выбранных корпоративных вики и систем управления задачами.
Выбраны MediaWiki и Redmine.

## Процесс установки.
### MediaWiki.
Скачивание архива с официального сайта.

![image](https://github.com/user-attachments/assets/63b195bc-e260-485c-8df0-d9e974173f48)

Извлечение архива.

![image](https://github.com/user-attachments/assets/499a2c61-f62e-4f52-a5b9-ce2a295ad597)

Для установки будет использоваться программа xampp, которую тоже нужно установить:

![image](https://github.com/user-attachments/assets/08284ee2-bea5-467e-b4a3-ea3525f2541a)

Копирование содержимого архива в следующую директорию:

![image](https://github.com/user-attachments/assets/aed85cba-cdf6-49ef-b7e8-b40435ef1200)

В xampp запуск Apache и MySQL:

![image](https://github.com/user-attachments/assets/ca13826f-4879-48c9-9d1e-21af60f7ffc5)

Переход по адресу localhost/phpmyadmin/:

![image](https://github.com/user-attachments/assets/934c8593-3ddf-469a-a5b0-cbff7317769b)

Добавление учетной записи MediaWiki:

![image](https://github.com/user-attachments/assets/b51e019f-90fa-4fb1-b20d-7d54e775a5a0)

Установка MediaWiki по следующему адресу:

![image](https://github.com/user-attachments/assets/56533ce6-5fdf-4c44-99d6-01d3ed25ea41)

Результат настройки MediaWiki:

![image](https://github.com/user-attachments/assets/e0ef5385-3413-4dac-ab39-c13537b8b2d1)

Добавление файла LocalSettings.php к файлу index.php в директории mediawiki-example:

![image](https://github.com/user-attachments/assets/6f9f38c7-641e-4d8f-8b9b-96044123c465)

Результат установки:

![image](https://github.com/user-attachments/assets/044b72e6-954b-45c6-8a5b-d274171c8c6f)


## Функциональный анализ.
1. **Краткое описание возможностей каждой системы**:
MediaWiki — это система управления контентом, ориентированная на создание и редактирование вики-страниц, которая поддерживает совместную работу, версионность и расширяемость через плагины; Redmine — это система управления проектами, которая предлагает функции отслеживания задач, управления проектами, ведения документации и интеграции с системами контроля версий.
2. **Оценка удобства использования, возможностей по настройке и управления доступом**:
MediaWiki обладает интуитивно понятным интерфейсом для редактирования страниц, но может потребовать времени на изучение более сложных функций; Redmine предлагает гибкие возможности настройки интерфейса и управления доступом, позволяя администраторам задавать права для пользователей и групп, что делает его удобным для различных команд.
3. **Описание основных функций, которые можно использовать в корпоративной среде**:
4. В MediaWiki можно использовать функции совместного редактирования, ведения документации и создания базы знаний, тогда как Redmine предоставляет инструменты для планирования проектов, отслеживания задач, ведения отчетности и интеграции с другими системами, что делает его идеальным для управления проектами в корпоративной среде.

## Вывод.
MediaWiki
Преимущества:
  - Мощный инструмент для создания и управления вики-контентом.
  - Отличные возможности для совместной работы.
  - Расширяемость через плагины и расширения.
  - Поддержка версионности страниц.

Недостатки:
  - Сложность освоения для пользователей, не знакомых с продвинутыми функциями.
  - Требует времени на настройку и администрирование.

Redmine
Преимущества:
  - Обширные возможности для управления проектами и задачами.
  - Гибкая настройка интерфейса и управления доступом.
  - Интеграция с системами контроля версий (например, Git).
  - Удобные инструменты для ведения отчетности и мониторинга прогресса.

Недостатки:
  - Интеграция с другими системами может потребовать дополнительных усилий.
  - Может быть сложным для пользователей, не имеющих опыта работы с системами управления проектами.

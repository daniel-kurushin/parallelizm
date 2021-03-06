# Понятие высокопроизводительной системы

- High-Perfomance application - приложение с высокой производительностью.
- High-Load application - приложение с высокой нагрузкой.
- High-Availability application - приложение с высокой доступностью.

http://codenet.ru/webmast/php/perfomance/

## High-Perfomance application

High-Perfomance application - приложение с высокой производительностью.

Производительность - продуктивность производственной деятельности, измеряемая
количеством продукции, произведенной за единицу времени.  Т.о.
"производительность приложения" - количество некоторых элементарных операций
обслуживания клиента в единицу времени. 

Ср. "производительность вычислителя" - FLOPS (также flops, flop/s, флопс или
флоп/с; акроним от англ. FLoating-point Operations Per Second, произносится
как флопс) -  единица, используемая для измерения производительности
компьютеров, показывающая, сколько операций с плавающей запятой в секунду
выполняет данная вычислительная система. Поскольку современные компьютеры
обладают высоким уровнем производительности, более распространены производные
величины от флопс, образуемые путём использования приставок СИ. 

*ИЛИ*

	$ cat /proc/cpuinfo | grep bogo
	bogomips	: 6187.55
	bogomips	: 6187.55
	bogomips	: 6187.55
	bogomips	: 6187.55

BogoMIPS (от англ. bogus (поддельный) и MIPS - англ. Millions of Instructions
Per Second) - в ядре Линукс способ измерения скорости исполнения инструкций на
компьютере, предназначенный для калибровки внутренних циклов.

Когда мы говорим о производительности процессоров - все более-менее понятно
(на самом деле - нет). Почему, когда речь идет о производительности приложений
такая путаница? Вероятно потому, что отдельные операции приложения никому не
нужны, а в реальных условиях приложения работают под некоторой нагрузкой,
которая  влияет на впечатления пользователя от его работы.

Т.о. непосредственно "производительность" приложения не имеет смысла
рассматривать в отрыве от нагрузки. Тем не менее "высокопроизводительное"
приложение - такое, что выполняет много элементарных операций в единицу
времени.

"Много" - это сколько?

## High-Load application

High-Load application - приложение с высокой нагрузкой.

## High-Availability application

High-Availability application - приложение с высокой доступностью.

# Управление производительностью приложения

## Зависимость цены исправления ошибок от стадии обнаружения и стадии внесения.

## Основные характеристики, описывающие производительность системы;

## Модель производительности системы.

## Анализ требований для высокопроизводительных систем

### Формирование нефункциональных требований для высокопроизводительных систем;

### Работа с противоречиями при формировании требований к производительности;

### Полнота требований.

# Лабораторная работа "Анализ требований на противоречивость и полноту".

# Проектирование высокопроизводительных систем:

## Атрибуты качества системы;

## Основные причины потери производительности системы;

## Основные методы повышения производительности системы.

# Лабораторная работа "Построение алгоритма сортировки объектов с использованием параллельного выполнения сортировки. Анализ построенного алгоритма"

# Лабораторная работа "Определение оценок количественных характеристик доступа к записям базы данных с использованием индексов. Анализ зависимостей времени доступа от длины ключа и количества записей в БД"

# Шаблоны для реализации высокопроизводительных систем

## Основные классы шаблонов, используемые при построении высокопроизводительных систем:

- GRASP;
- Architecture patterns;
- Application Integration patterns.

## Примеры практической реализации шаблонов в современных стандартах.

## Примеры практической реализации шаблонов в современных системах интеграции frameworks-разработки.

# Лабораторная работа "Оптимизация производительности приложения, выполняющего последовательную обработку большого объема информации".

# Кодирование высокопроизводительных систем:

## Основные вопросы кодирования высокопроизводительных систем.

## Методы оптимизации современных компиляторов и сред выполнения.

# Тестирование высокопроизводительных систем:

## Виды тестов, используемые при доказательствах производительности системы.

## Подготовка к тестированию (составление сценариев и формирование модели нагрузки).

## Анализ результатов тестирования.

# Оптимизация производительности для приложений:

## Оптимизация производительности системы;

## Пути оптимизации производительности сложных распределенных систем;

## Оптимизация и повышение стабильности работы Java-приложений;

## Повышение производительности баз данных.

# Методология SPE:

## Введение в методологию SPE. История, границы использования;

## Модель производительности системы;

## Применение модели производительности системы при анализе современных систем;

## Применение SPE при разработке современных систем;

## Методика анализа систем с использованием SPE.

# Лабораторная работа "Построение модели производительности тестовой системы".

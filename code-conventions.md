1. Code convention - что это.
2. Плюсы использования, основы написания.


# Набор правил форматирования #

Обычно покрывают организацию файлов, отступы, комментарии, декларации, операторы, пробелы, правило наименования (CamelCase / snake_case),
Сильно повышает читабельность и облегчают поддержку исходного кода. Можно формализовать в виде документа, а можно нет.



## Programming principles: ##

### принципы SOLID ###

Принцип единой обязанности


### Зачем они нужны ###




## Programming rules of thumb: ##


## Code smell ##

	часто указывает на то, что в системе существует более глубокая проблема
		определенные структуры в коде, которые указывают на нарушение фундаментальных принципов дизайна и негативно влияют на качество продукта
		Обычно не баги.


### Уровень приложения: ###

  * Дублирование кода
  * Надуманная сложность (contrived complexity)


### Уровень класса: ###

  * Большие классы (! single responcibility)
  * Feature envy: a class that uses methods of another class excessively. (класс использует методы другого класса слишком интенсивно)
  * Inappropriate intimacy: a class that has dependencies on implementation details of another class. (класс который зависит от деталей реализации другого класса)
  * Refused bequest: a class that overrides a method of a base class in such a way that the contract of the base class is not honored by the derived class. See Liskov substitution principle. (! Liskov principle) (Класс который переопределяет метод родителя таким образом, что нарушается интерфейс родителя. 
  * Lazy class / Freeloader: a class that does too little. Класс который делает слишком мало
  * Excessive use of literals: these should be coded as named constants, to improve readability and to avoid programming errors. Additionally, literals can and should be externalized into resource files/scripts where possible, to facilitate localization of software if it is intended to be deployed in different regions. -- чрезмерное использование литералов. Вместо них лучше использовать именованые константы. 
  * Cyclomatic complexity: too many branches or loops; this may indicate a function needs to be broken up into smaller functions, or that it has potential for simplification. Вероятное укзазывает на то что цикл нужно разбить на несколько функций, или на то что что-то можно упростить.


### Уровень функции/метода ###

  * Слишком много параметров
  * Слишком длинный метод
  * Слишком короткое или длинное имя параметра или метода
  * Чрезмерные возвращаемые данные -- когда метод или функция возвращает больше чем нужно вызывающему коду


# PHPStorm #

Editorconfig plugin

## EditorConfig plugin ##

http://editorconfig.org/


# Others #

psr-2 vs ours
spaces
tools for automation
pluses and minuses
naming



# SOLID #

## Принцип единой обязанности ##


Use your head!

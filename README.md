# java8_ArrayList
С предыдущей лабороторной работы Java7_Preparation_DataBase Модифицировали проверки в setter'ax для nameCountry & capital 
С помощью регулярных выражений. Переопределили метод toString для вывода объектов и так же добавили метод State для ввода всех наших значений в объект
Создали класс stateArraylist {
  * Метод для добавление новых объектов addStateList();
  * Метод удаление всех стран у которых население меньше заданного значения deleteAllCountryPopulationLess();
  * Метод поиска объекта по значению capital searchNameCapital();
  * Метод поиска всех элементов объекта по площаде выше заданной searchByOccupiedSpaceOver();
  * Метод вывод всех государств введенного материка с отсортированными объектами и с выбором сортировки 
    (по названию, по площади, по населению) реализован с переключателем от 1 до 3
    sortCountryContinents(String continent, int n) , где continent - значение континента, n - значение выбора сортировки
  * Метод вывода всех записанных объектов в Arraylist showStatesList();
}
1. Напишите программу, которая считывает текст из файла (в файле может быть больше одной строки) и выводит в новый файл самое часто встречаемое слово в каждой строке и число – счётчик количества повторений этого слова  в строке. 
2. Напишите программу, которая получает на вход строку с названием текстового файла и выводит на экран содержимое этого файла, заменяя все запрещённые слова звездочками. Запрещённые слова, разделённые символом пробела, должны храниться в файле stop_words.txt. Программа должна находить запрещённые слова в любом месте файла, даже в середине другого слова. Замена независима от регистра: если в списке запрещённых есть слово exam, то замениться должны exam, eXam, EXAm и другие вариации. 
	Пример: в stop_words.txt записаны слова: hello email python the exam wor is
Текст файла для цензуры выглядит так: Hello, World! Python IS the programming language of thE future. My EMAIL is… PYTHON as AwESOME! 
Тогда итоговый текст: *****, ***ld! ****** ** *** programming language of *** future. My ***** **... ****** ** awesome!!!!
3. В текстовый файл построчно записаны фамилия и имя учащихся класса и оценка за контрольную. Вывести на экран всех учащихся, чья оценка меньше трёх баллов. 
4. В файл записано некоторое содержимое (буквы, цифры, пробелы, специальные символы и т.д.). Числом назовём последовательность цифр, идущих подряд. Вывести сумму всех чисел, записанных в файле. 
Пример: входные данные: 123 ааа456 1x2y3z 4 5 6
Выходные данные: 600
5. Дан текстовый файл с несколькими строками. Зашифровать шифром Цезаря, при этом шаг зависит от номера строки: для первой строки шаг 1, для второй – 2 и т.д.
Пример:  
![image](https://github.com/ChelGPT-5/8/assets/125600788/3984ba55-f1f3-4c46-be5d-6d892a6c429e)
6. JSON и CSV. 
Исходные данные тут 
Пункты задания:
	0. Есть данные в формате JSON – взять с диска с исходными данными. 
	1. Реализовать функцию, которая считает данные из исходного JSON-файла и преобразует их в формат CSV
	2. Реализовать функцию, которая сохранит данные в CSV-файл (данные должны сохраняться независимо от их количества – если добавить в исходный JSON-файл ещё одного сотрудника, работа программы не должна нарушаться).
	3. Реализовать функцию, которая добавит информацию о новом сотруднике в JSON-файл. Пошагово вводятся все необходимые данные о сотруднике, формируются данные для записи. 
  4. Такая же функция для добавления информации о новом сотруднике в CSV-файл. 
	5. Реализовать функцию, которая выведет информацию об одном сотруднике по имени. Имя для поиска вводится с клавиатуры. 
	6. Реализовать функцию фильтра по языку: с клавиатуры вводится язык программирования, выводится список всех сотрудников, кто владеет этим языком программирования. 
	7. Реализовать функцию фильтра по году: ввести с клавиатуры год рождения, вывести средний рост всех сотрудников, у которых год рождения меньше заданного. 
  8. Программа должна представлять собой интерактив – пользовательское меню с возможностью выбора определённого действия (действия – функции из предыдущих пунктов + выход из программы). Пока пользователь не выберет выход из программы, должен предлагаться выбор следующего действия.

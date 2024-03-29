# 1. ОПИСАНИЕ.
Web-приложение, на основе Streamlit. Осуществляет поиск ответа на заданный вопрос в пользовательском тексте.
ПРАКТИЧЕСКОЕ ЗАДАНИЕ №2 по дисциплине "Программная инженерия" магистратуры "Инженерия машинного обучения" Уральского Федерального Университета. Работу выполнили студенты 1-го курса магистратуры:
- Колганов Максим Валерьевич, группа: РИМ-120963
- Шалагин Дмитрий Алексеевич, группа: РИМ-120963

# 2. ЗАПУСК.
## 2.1. С помощью библиотеки Streamlit.
Поскольку данное приложение уже развернуто на streamlit - просто воспользуйтесь [ссылкой](https://question-answerer.streamlit.app/).

## 2.2. Через командную строку.

1. Нажмите на клавиатуре клавиши `"Win" ` и `"R"`.
2. Откроется окно `"Выполнить"`.
3. Впишите в него команду `cmd` и нажмите `"ОК"`.
4. Перейдите в папку с файлом проекта: `cd <путь_к_папке_проекта>`
5. Выполните: `streamlit run <имя_файла>`

# 3. ИСПОЛЬЗОВАНИЕ.

* Поле `CONTEXT`: текст, в котором будет осуществляться поиск ответа (только на английском).
* Поле `QUESTION`: вопрос, на который будет осуществляться поиск ответа
	 в тексте из поля `CONTEXT` (только на английском).
* В результате получаем `ANSWER` (ответ на вопрос) и `SCORE` (оценка для данного ответа).

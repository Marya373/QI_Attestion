#Промежуточная аттестация по курсу тестирование

# Урок 1. Приложение заметки (Python) "Task 1"
В данном коде представлено консольное приложение для работы с текстовыми файлами. 

Здесь создается окно `main_application`, где пользователь может открыть, сохранить, сохранить как, редактировать и удалить файл. В меню `file` добавлены команды для выполнения этих действий. Также в окне предоставляется редактор для ввода и редактирования текста с использованием виджета `Text`.

В функции `clear_file` выполняется очистка окна редактора и сброс глобальной переменной `url`, содержащей текущий путь к файлу.

В функции `open_file` пользователю предлагается выбрать файл через диалоговое окно `filedialog.askopenfilename()`. Если файл успешно выбран, то его содержимое отображается в редакторе. Заголовок окна устанавливается в название выбранного файла.

Функция `save_file` сохраняет содержимое редактора в текущем файле, если он уже существует, или сохраняет его через диалоговое окно `filedialog.asksaveasfile()`, если файл еще не был сохранен. Если файл успешно сохранен, то глобальная переменная `url` устанавливается на путь к сохраненному файлу.

Функция `save_as` предоставляет пользователю возможность сохранить текущее содержимое редактора в новый файл через диалоговое окно `filedialog.asksaveasfile()`.

Функция `changed` отслеживает изменения в редакторе и устанавливает значение `text_changed` в `True`, если текст был изменен.

Функция `exit_func` вызывается при попытке закрыть приложение. Если содержимое редактора было изменено, пользователю будет предложено сохранить изменения. Если пользователь выберет "Да", то содержимое редактора будет сохранено в текущем файле или в новом файле через диалоговое окно `filedialog.asksaveasfile()`. Если пользователь выберет "Нет", то изменения не будут сохранены, а приложение закроется. Если пользователь выберет "Отмена", то закрытие приложения будет отменено. Если содержимое редактора не было изменено, то приложение закроется без предупреждений.

# Урок 2. Магазин игрушек (Java) "Task 2"





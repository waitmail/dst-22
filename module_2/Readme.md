Задача скачала в том чтобы в том чтобы скачать датасет.
Проанализировать его и выбрать признаки для построения модели.
Сразу был удален столбец 'studytime, granular' так ка его нет в описании датасета.
Затем были преобразованы имена колонок к нижнему регистру, для удобства обращения к ним.
При анализе исходного датасета пропущенные значения были зхаполнены 
МОД(ой) некоторые ошибочные значения в столбцах были заменены на те которые показались 
мне более правильными.
Были определены колонки которые являются номинативными, это по моему мнению все колонки кроме 
['age','absences','score'].
Был произведен анализ данных в номинативных колонках путем построения графиков и зрительного анализа.
Считаю, что по отрисовке функцией get_boxplot значимыми стоит считать 
medu,fedu,studytime,failures,higher ,freetime,goout,health.
Была произведена проверка этих признаков(содержимое этих колонок) с помощью теста Стьюдента.
По итогу этого теста значитмые признаки это ['medu', 'failures', 'higher'].
Эти признаки необходимо использовать при построении модели.
Так была проверка на корреляцию количественных признаков при построени модели 
необходимо учитывать признаки absences и age.
Задание было трудным, это мой первый опыт в EDA еще много непонятного с чем предстоит разобраться.
Очень сильно помогает в понимании общение с коллегами.Менторы помогают направить ход мыслей в нужную сторону. 

   
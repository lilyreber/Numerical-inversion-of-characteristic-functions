# Пакет для численного обращения характеристических функций


Характеристическая функция – это преобразование Фурье распределения случайной величины. Один из способов задания закона распределения – это задание характеристической функции. Во многих вероятностных моделях нам доступны только характеристические функции, а не сами плотности, что усложняет процесс моделирования и оценку числовых характеристик. Восстановление функции распределения или плотности случайной величины по ее характеристической функции аналитическими методами зачастую является крайне сложной задачей, поэтому приходится прибегать к использованию численных методов.

В рамках проекта планируется создать инструмент, реализующий различные методы обращения характеристических функций и провести численный анализ на разных классах распределений. В особенности хочется провести сравнение этих методов при работе с безгранично делимыми распределениями, которые все чаще применяются в моделях машинного обучения и стохастического анализа.


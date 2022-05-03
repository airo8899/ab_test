# ab_test

### Проверка гипотезы об увеличении CTR при использовании новых алгоритмов рекомендации постов.

Были сделаны два новых алгоритмов рекомендации постов для увеличения интереса пользователей к постам. В качестве метрики используется CTR. 
Пользователи были разбиты на 4 группы системой случайного сплитования:
* 0, 1 - контрольные группы.
* 2 -  алгоритм рекомендации постов,  которые похожи на часто лайкнутые 
* 3 -  алгоритм рекомендации постов, которые лайкали похожие на вас люди

АА-тест проходил с 8 по 14 марта 2022.
АБ-тест с системами рекомендаций проходил с 15 по 21 марта 2022.

Использованные методы исследований: t-тест Стьюдента, U-тест Манна-Уитни, бутстреп, сглаживание Лапласа, бакетное преобразование и линеаризация значений метрики.


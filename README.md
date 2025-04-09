# qa_manual_coursework
Моя курсовая работа по завершении модуля "ручное тестирование веб-приложений" на Нетологии

Задание 1<br>
Написать чеклист для функциональной проверки личного кабинета зарегистрированного авторизованного пользователя, включая функционал разделов, на сайте https://henderson.ru/.

Задание 2<br>
2.1. Необходимо написать набор тест-кейсов на проверку функционала авторизации на сайте Хендерсон. Обратите внимание, что проверки должны покрывать как позитивные, так и негативные проверки, а также при написании тестов вам нужно использовать изученные практики тест-дизайна. Проверки должны быть атомарными, а также учитывать проверку процесса авторизации от начала до конца. Помните, что задача - в первую очередь проверить функциональность, а не верстку. Ваша задача — написать минимум 10 тест-кейсов.

2.2.* Разработчики решили в будущем добавить новую функциональность на сайт, но пока у нас в распоряжении есть только техническое задание, оно же - требования. Пока они недоработаны, но мы уже можем начать процесс тестрования требований. ссылке Напишите свои вопросы по этим требованиям. Они могут касаться не описанных, но важных сценариев, граничных значений и подобных проблем, по аналогии с ДЗ.

Задание 3<br>
3.1. На основе скриншота создайте не менее трёх баг-репортов. Обратите внимание, что здесь в окружении мы можем описать тот браузер, с которого проводилась бы проверка, то есть ваш актуальный.

3.2.* Найдите баг в функции «Написать отзыв» в карточке товара и составьте на него баг-репорт. Если найдёте несколько — замечательно!

Задание 4<br>
Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте сейчас товаров с такой ценой нет, а разработчик бэкенда в отпуске, поэтому вам нужно протестировать вёрстку страницы карточки товара с максимальной и минимальной ценой самостоятельно. Ваша задача — самостоятельно определить, как проще это сделать, и предоставить решение в виде скриншотов страницы карточки товара с минимальной и максимальной ценой. Важно, чтобы было видно, с помощью чего вы изменили эту цену.

Задание 5<br>
Бэкенд-разработчик говорит, что мы отправляем данные с сайта в неправильном формате, и просит вас помочь найти нужный запрос. Фронтенд-разработчик ушёл в отпуск в поход без связи, а документация пропала.

Известно, что проблема в данных, которые уходят в POST запросе по адресу, который начинается с https://api.mindbox.ru/. Происходит это, скорее всего, при работе с личными данными пользователя, например, авторизацией, личным кабинетом, просмотром корзины.

Ваша задача — изучить ответы и запросы при работе с сайтом, найти запрос, в котором есть нужные параметры, найти, как же выглядят параметры deviceUUID, requestID и status, и приложить скриншот искомого превью в таблицу с решениями.

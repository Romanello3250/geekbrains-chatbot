# Канал Jivosite

**Задача:**
Подключить онлайн-чат от Jivosite как канал коммуникации с ecom-чатботом

[Документация](https://www.jivo.ru/help/api/bot-api.html)

#### 1. Подключение:

- [ ] Сделать web-страничку с подключенным Jivosite
- [ ] Получить входящий Webhook
- [ ] Отправить сообщение

#### 2. Echo-bot:

- [ ] Текст
- [ ] Ссылка
- [ ] Картинка
- [ ] Файл

#### 3. Получение данных пользователя

- [ ] ФИО / имя
- [ ] Аватар
- [ ] Страница сайта

#### 4. Кнопки:

- [ ] TODO: понять, какие кнопки поддерживаются

#### 5. Прочие события / операции:

- [ ] Переключить на оператора
- [ ] Оператор подключился
- [ ] Сообщение от оператора

### Пример диалога с ботом №1:

```
- Здравствуйте
- Здравствуйте, Евгений! Выберите категорию товаров: ...
- <кликнул на кнопку>
- Выберите товар: ...
- <кликнул на кнопку>
- Оплатите товар по ссылке: ...
- <произвел оплату>
- Спасибо! Начать заново?
```

### Пример диалога с ботом №2:

```
- Здравствуйте
- Здравствуйте, Евгений! Выберите категорию товаров: ...
- asdfqwer
- Не удалось определить категорию, перевожу вас на оператора
- ... общение с оператором ...
- Спасибо! Начать заново?
```

### Пример диалога с ботом №3:

```
- Здравствуйте
- Здравствуйте, Евгений! Выберите категорию товаров: ...
- asdfqwer
- Не удалось определить категорию и все операторы сейчас заняты.
- Начать заново?
```

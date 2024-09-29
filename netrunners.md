## Страница объявления

![product_page.png](static/product_page/product_page.png)

1. **На странице отображаются:**
   * Данные о товаре (Название, фото, город, описание, категория, цена и кол-во просмотров)
   * Данные о продавце (имя, почта и дата публикации объявления)
   * История цен
   * Кнопка добавления товара в корзину

### Баги страницы
* Некорректное отображение истории цен

![img.png](static/product_page/price_history.png)
* При попытке добавить товар в корзину без авторизации было бы целесообразнее сообщать, что требуется авторизация, или сразу перенаправлять пользователя на страницу авторизации

![img.png](static/product_page/add_to_cart.png)
### Баги с добавлением в избранное
* При попытке добавить товар в избранное без авторизации не возникает никаких ошибок или предупреждений со стороны интерфейса

![add_to_favourites_no_auth.png](static/product_page/add_to_favourites_no_auth.png)


### Баги с созданием объявления
* Имеется возможность в поля с названием и описанием добавить zalgo текст

![zalgo_check.png](static/product_page/zalgo_check.png)

* Не юзер френдли сообщение об ошибке

![create_product_error.png](static%2Fproduct_page%2Fcreate_product_error.png)

### Положительные кейсы
* Корректное отображение добавления в избранное авторизованным пользователем

![add_to_favourites_success.png](static/product_page/add_to_favourites_success.png)


## Страница настроек пользователя

1. **На странице отображаются:**
   * Поле вставки изображения для аватара
   * Поле ввода имени
   * Поле ввода телефона
   * Поле ввода почты
   * Кнопки сохранить и отменить изменения
   
![settings.png](static%2Fsettings%2Fsettings.png)

### Поле аватара
* При попытке загрузить слишком большой файл не возникает никаких ошибок или предупреждений со стороны интерфейса

![avatar_field.png](static%2Fsettings%2Favatar_field.png)

### Поле телефона
* Нет никакой валидации

![phone_field.png](static%2Fsettings%2Fphone_field.png)

### Поле почты
* при вводе новой почты данные записываются в номер телефона (+ отсутствует валидация)

![email_field_before.png](static%2Fsettings%2Femail_field_before.png)

![email_field_after.png](static%2Fsettings%2Femail_field_after.png)
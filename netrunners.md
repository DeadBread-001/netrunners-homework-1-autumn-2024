## Страница объявления

![product_page.png](static/product_page/product_page.png)

**На странице отображаются:**
   * Данные о товаре (Название, фото, город, описание, категория, цена и кол-во просмотров)
   * Данные о продавце (имя, почта и дата публикации объявления)
   * История цен
   * Кнопка добавления товара в корзину

### История цены
При нажатии на кнопку "история цены" появляется всплывающее окно с графиком

![price_history_graph.png](static/product_page/price_history_graph.png)

### Избранное
Корректное отображение добавления в избранное авторизованным пользователем

![add_to_favourites_success.png](static/product_page/add_to_favourites_success.png)

### Баги страницы объявления
* Некорректное отображение истории цен

![img.png](static/product_page/price_history.png)

* При попытке добавить товар в корзину без авторизации было бы целесообразнее сообщать, что требуется авторизация, или сразу перенаправлять пользователя на страницу авторизации

![img.png](static/product_page/add_to_cart.png)

* При попытке добавить товар в избранное без авторизации не возникает никаких ошибок или предупреждений со стороны интерфейса

![add_to_favourites_no_auth.png](static/product_page/add_to_favourites_no_auth.png)

* Имеется возможность в поля с названием и описанием добавить zalgo текст

![zalgo_check.png](static/product_page/zalgo_check.png)

* Не юзер френдли сообщение об ошибке

![create_product_error.png](static/product_page/create_product_error.png)


## Страница настроек пользователя

1. **На странице отображаются:**
   * Поле вставки изображения для аватара
   * Поле ввода имени
   * Поле ввода телефона
   * Поле ввода почты
   * Кнопки сохранить и отменить изменения
   
![settings.png](static/settings/settings.png)


### Баги страницы настроек
* При попытке загрузить слишком большой файл не возникает никаких ошибок или предупреждений со стороны интерфейса

![avatar_field.png](static/settings/avatar_field.png)

* Нет никакой валидации

![phone_field.png](static/settings/phone_field.png)

* при вводе новой почты данные записываются в номер телефона (+ отсутствует валидация)

![email_field_before.png](static/settings/email_field_before.png)

![email_field_after.png](static/settings/email_field_after.png)
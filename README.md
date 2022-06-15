# Тестирование API, запросы и ответы к сервису jsonplaceholder при помощи Postman
В запросе методом GET мы хотим узнать информацию на сайте о пользователе под id=2. Нам пришел ответ в формате json, что пользователя зовут Ervin Howell, его username Antonette и тд.
![_42Y67ZJkZNDy3kLhhgf-nrt0hrJxklSYpWth-I2kdbjz0SxFAHOwEeRGVGjp7RZsK7yJfR55rMsupPG7_WcFgvV](https://user-images.githubusercontent.com/101330984/173864725-0173d5b7-892c-43ec-b67a-c302c2a52e1f.jpg)
В запросе методом POST мы создаем новый пост, указываем в body информацию, которую хотим передать, а именно: title, body, userid
![yQ_GosP3Wzm3Nht46BjB4AUnLyiQAwkXqj3kPvuMjG1PdvIMHYOSR9P3n92ryvE1ItyU6skpPm74ZLPJdnRrEM_W](https://user-images.githubusercontent.com/101330984/173865368-1e21de90-5ca0-427f-81a5-58f08bebe98f.jpg)
В запросе методом PUT мы вносим изменения в существующий пост заменив в нем title на “FOO”, отобразив это в body
![4beTL1y3Xm-yt_eJ_H5kt84B7IXgBKzBPVxyt_lW9Rl_foC3pcoVKpcgZu5_snBcoIZvfT1nGWk5LnG_BtsgZm2U](https://user-images.githubusercontent.com/101330984/173865545-00a2ad21-f120-445d-90f7-384c806c722f.jpg)
В запросе методом DELETE мы удаляем пост, который загрузили выше, указав в URL post и его id
![7AgSuhiogKqw2GdGfAWc04D1aiJUY4k-sSS-VYKBczqmyIdFywhGek5ywGakVbOAHoZZTViqKMrX12W2UyM8vI3R](https://user-images.githubusercontent.com/101330984/173865676-00fa5810-d8a8-4d0b-b7a4-05e2c1b892ee.jpg)

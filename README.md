# linux-premissions-hw
HW linux premissions for TMS
<br>
<br>
1) Создать пользователя `vally` с домашним каталогом и оболочкой `/bin/bash`; задать пользователю пароль

<img width="628" height="260" alt="изображение" src="https://github.com/user-attachments/assets/0448ffa3-952b-4eed-ac5e-6d5bfeb7ce07" />
<br>
<br>

2) Создать ползователя `eve` без домашнего каталога (`useradd` без ключей)

<img width="601" height="119" alt="изображение" src="https://github.com/user-attachments/assets/aa2b76cb-1783-49cc-a60f-f1e0d9979f35" />
<br>
<br>

3) Создать директорию `/home/eve`, дать пользователю `eve` права на него

<img width="598" height="275" alt="изображение" src="https://github.com/user-attachments/assets/bedb20c1-dff1-44d9-a544-77b4f736d7a7" />
<br>
<br>

4) Переименовать пользователя `vally` в `robot` и проверить, изменился ли UID

<img width="541" height="101" alt="изображение" src="https://github.com/user-attachments/assets/2fb3e120-558e-4bf7-bafd-0a187255d9c8" />
<br>
<br>

5) Создать группу `tms`

<img width="618" height="185" alt="изображение" src="https://github.com/user-attachments/assets/ed6ab73b-b336-4d8c-8ed1-9382e859c91f" />
<br>
<br>

6) Добавить пользователя `robot` в группу `tms`

<img width="617" height="148" alt="изображение" src="https://github.com/user-attachments/assets/cc759c2e-1196-460e-823c-8d21bb30a988" />
<br>
<br>

7) Создать директорию `/var/www/projects` и в ней
- файл `readme.md`
- файл `secret`
- директорию `bot-hub`
- файл  `bot-hub/app.py`

<img width="616" height="404" alt="изображение" src="https://github.com/user-attachments/assets/fb26075f-e47e-4f29-bb18-38c9973fb6f6" />
<br>
<br>

8) Установить права на файл `secret` так, чтобы только владелец мог читать и изменять его

<img width="624" height="165" alt="изображение" src="https://github.com/user-attachments/assets/816b97a9-0a21-4401-a120-6d2ad7f323b1" />
<br>
<br>

9) Установить права на файл `readme.md` так, чтобы группа могла читать и изменять его (у владельца права не отбирать)

<img width="624" height="165" alt="изображение" src="https://github.com/user-attachments/assets/98c643c1-1fd0-4e8a-869e-b5dc150e8f7f" />
<br>
<br>

10) Уставновить права на `bot-hub` так, чтобы ни у одной категории пользователей не было бита `x`

<img width="624" height="165" alt="изображение" src="https://github.com/user-attachments/assets/0be0838d-5961-4b8a-9012-dd408be26b31" />
<br>
<br>

11) Попробовать зайти в `bot-hub`; сделать `ls -l bot-hub`

<img width="624" height="165" alt="изображение" src="https://github.com/user-attachments/assets/54fee9d1-fcc4-46a6-8ecc-3528fd132130" />
<br>
<br>

12) Вернуть файлу `bot-hub/app.py` бит `x` для владельца и группы; повторить п.11

<img width="664" height="321" alt="изображение" src="https://github.com/user-attachments/assets/b3073e74-dfa4-45bc-92ea-dd1c8f4d3ddc" />
<br>
<br>

13) Назначить директоии `/var/www/projects` рекурсивно группой владельцев `tms`

<img width="771" height="400" alt="изображение" src="https://github.com/user-attachments/assets/e5e5f7ee-8ccc-4346-b924-448c00e6db2a" />
<br>
<br>

14) Назначить владельцем файла `secret` пользователя `robot`, а владельцем `readme.md` - `eve`

<img width="674" height="208" alt="изображение" src="https://github.com/user-attachments/assets/5ebd55a6-9885-443c-b07f-7d091d881c9b" />

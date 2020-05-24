# Изменение контента для страницы irynahala.info

Изменения необходимо вносить в ветку gh-pages.

Соответствие между страницами на сайте и файлами в репозитории (папке):

 - index.html - английский
 - de.html - немецкий
 - ru.html - русский

## Краткое руководство по внесению изменений

### В локальной копии

- перейти в локальную папку репозитории в FreeCommander (сейчас *D:\Ira\irene-design*)
- В коммандной строке (внизу) написать `git gui` и нажать ***Enter***

**Копирование последней версии из GitHub (По необходимости)**

- В ***Git Gui*** нажать ***Tools -> gitt pull***

**Внесение изменений**

- Открыть нужный файл в Notepad++ или другом текстовом редакторе.
- Внести и сохранить изменения.
- Открыть измененный файл в браузере (например Firefox) и проверить вид страницы.

**Копирование изменений в GitHub**

- В ***Git Gui*** 
	- нажать ***Rescan***
	- В открывшемся окне слева сверху выбрать измененные файлы и нажать ***Stage changed***.
	- Измененные файлы должны перейти с левого верхнего в левое нижнее окно.
	- В правом нижнем окне (***Commit message***) кратко описать сделанные инменения (например: *update of russian page*).
	- Нажать ***Commit***
	- Нажать ***Push***
	- В меню **Source Branches** выбрать **gh-pages**.
	- Нажать ***Push***.

- Проверить обновленную страницу ***irynahala.info***.

### Непосредственно в GitHub репоситории

- в браузере переидти на страницу *https://github.com/katherling/irene-design/tree/gh-pages*
- войти в GitHub аккаунт.
- выбрать нужный файл
- нажать ***Edit*** (карандаш)
- Внести изменения.
- Внизу страницы добавить короткое сообщение об изменениях.
- Нажать ***Commit changes***
- Проверить обновленную страницу ***irynahala.info***.
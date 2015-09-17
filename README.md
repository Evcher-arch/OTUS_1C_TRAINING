## Шаблон для работы правильного 1С разработчика

* содержит выработанную и обдуманную семантически структуру каталогов
* содержит необходимые подмодули для быстрого старта

### Порядок установки

* прочитайте [Wiki](https://github.com/silverbulleters/vanessa-bootstrap/wiki/%D0%A0%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8-%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D1%8C%D0%BD%D1%8B%D0%BC-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%D0%B0%D0%BC-1%D0%A1)
* склонируйте репозиторий

```Shell
git clone https://github.com/silverbulleters/vanessa-bootstrap.git <название-вашего-продукта-1С>
```
* подключите репозиторий к своему git серверу (GitHub, Bitbucket, GitLab, etc)

```Shell
cd <название-вашего-продукта-1С>
git remote set-url origin git://new.url.here
```

* не забудьте подписаться на обновление шаблона

```
git remote set-url bootstrap https://github.com/silverbulleters/vanessa-bootstrap.git
```

теперь вы можете начинать разрабатывать по правильному и быть подписанными на любые изменениями.

### Порядок обновления

Чтобы получить изменения каталога 

```Shell
git pull bootstrap <ваша текущая ветка разработки>
```

### Возможности доработки шаблона

* откройте issue - тогда можно обсудить необходимость адаптации под ваши задачи
* войдите в чат Gitter - чтобы задать дополнительные вопросы 
* сделайте fork, внесите изменения и выполните pull request с предлагаемыми вами изменениями (fork и pull request - это кнопки на GitHub.)

### Заметки на полях

* структура в перспективе будет содержать и адаптацию семантики каталогов для проектов на проекте Graphite от компании 1С после появления официального стабильного релиза

~~~
TODO - дополнить и расширить описание и документацию
~~~
# drupal-console-ru

Drupal Console Russian Language / Drupal Console на русском языке

# Версия на русском языке

## Использование

По-умолчанию Drupal Console устанавливается на Drupal 8 сайты на английском языке.

Команда для установки Drupal Console на русском языке:

```
$ composer require drupal/console-ru
```

### Установка Drupal Console

Команда для установки Drupal Console используя composer:

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Устанока пуского файла Drupal Console

Пусковой файл Drupal Console был создан, чтобы избежать конфиликов между основными и придаточными версиями Drupal и различными версиями Drupal Console. Приемущество пускового файла в том, что команды Drupal Console доступны каждой установке Drupal на данной машине.

Команда для устновки пусковой файл Drupal Console глобально

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Содействие и помощь в разработке

Если Вы хотите помочь с переводом, следуйте иструкции

- [Минимальные требования](https://docs.drupalconsole.com/ru/contributing/project-requirements.html)
- [Установка проекта](https://docs.drupalconsole.com/ru/contributing/getting-the-project.html)
- [Использование проекта](https://docs.drupalconsole.com/ru/contributing/running-the-project.html)

Внимание: сохранияйте свои изменения в ответвленный код и создайте запорос на обновление родительского кода (pull request) своевременно (желательно, ежедневно), чтобы избежать конфликтов с родительским кодом и изменениями других разработчиков.

# Английская версия

Проект на английском доступен по ссылке [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
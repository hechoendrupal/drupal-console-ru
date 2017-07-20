# drupal-console-ru
DrupalConsole Russian Language / Pусский язык

# Версия на русском языке

## Использование

Команда для установки Drupal Console на русском языке:

```
$ composer require drupal/console-ru
```

### Установка Drupal Console

Команда для установки Drupal Console:

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Устанока пуского файла Drupal Console

Пусковой файл Drupal Console был создан, чтобы избежать конфиликов между основными и придаточными версиями Drupal и Drupal Console. Приемущество пускового файла в том, что команды Drupal Console доступны каждой установке Drupal на данной машине.

Чтобы устновть пусковой файл Drupal Console глобально, выполните ряд следующих комманд

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Содействие и помощь

Если Вы хотите помочь с переводом, следуйте иструкции

- Создайте ответвление кода. Инструкция по сслылке [https://github.com/hechoendrupal/drupal-console-ru#fork-destination-box](https://github.com/hechoendrupal/drupal-console-ru#fork-destination-box)
- Склонируйте код локально.
- Добавте родительский код (upstream) в отслеживаемые

Команда для добавления родительского кода (upstream) в отслеживаемые для своевременного уведомления об обновлениях родительского кода.

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-ru.git
```

Команда для скачивания последних обновлений родительского кода локально

```
$ git fetch upstream
$ git merge upstream/master
```

Внимание: сохранияйте свои изменения в ответвленный код и создайте запорос на обновление родительского кода (pull request) своевременно, чтобы избежать конфликтов с одительским кодом.

# Английская версия

Инструкция на английском доступна по ссылке [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)

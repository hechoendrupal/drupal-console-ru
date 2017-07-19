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

- Инструкция как создать ответвленFork this repository following this link [https://github.com/hechoendrupal/drupal-console-ru#fork-destination-box](https://github.com/hechoendrupal/drupal-console-ru#fork-destination-box)
- Clone your repostory forked in your local machine.
- Set up upstream

In order to be updated with other contribution you must to setup a connected with main repository using the following git command

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-ru.git
```

To fetch the latest contribution before to start, you must run the next commands
```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.

# Английская версия

Инструкция на английском доступна по ссылке [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)

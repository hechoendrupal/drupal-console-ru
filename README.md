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

Пусковой файл Drupal Console был создан, чтобы избежать конфиликов между основными и придаточными версиями Drupal и Drupal Console. 
In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal,  a Drupal Console launcher was created. n order to facilitate to load the Drupal Console commands available to each
Drupal 8 website,
 
Following the instruction below you could install the global application for Drupal Console launcher. 

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

If you want to contribute to this translation, you need to follow this steps

- Fork this repository following this link [https://github.com/hechoendrupal/drupal-console-ru#fork-destination-box](https://github.com/hechoendrupal/drupal-console-ru#fork-destination-box)
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

Инструкция на английском [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)

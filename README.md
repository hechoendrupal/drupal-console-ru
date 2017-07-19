# drupal-console-ru

Drupal Console Russian Language / Drupal Console на русском языке

# Версия на русском языке

## Использование

По-умолчанию Drupal Console устанавливается на Drupal 8 сайты в английском языке.

Для добавления поддержки русского языка в Drupal Console выполните следующую команду:

```
$ composer require drupal/console-ru
```

### Установка Drupal Console

Для установки нужной версии Drupal Console для вашей сборки Drupal выполните следующую команду с помощью composer:

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Установка файла запуска Drupal Console

Чтобы избежать конфликтов между мажорными и минорными версиями Drupal и различными версиями Drupal Console, был создан файл запуска Drupal Console для упрощения загрузки Drupal Console команд, доступных для каждого Drupal 8 сайта.
 
Вы можете установить глобальную программу для файла запуска Drupal Console, ипользуя приведенную ниже инструкцию:

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Помощь в разработке

Если вы хотите помочь с данным переводом, следуйте следующим шагам:

- [Минимальные требования](https://docs.drupalconsole.com/ru/contributing/project-requirements.html)
- [Установка проекта](https://docs.drupalconsole.com/ru/contributing/getting-the-project.html)
- [Использование проекта](https://docs.drupalconsole.com/ru/contributing/running-the-project.html)

Замечание: заливайте ваши изменения в ваш ответвленный репозиторий для создания PR ежедневно для избежания конфликтов с изменениями других разработчиков.

# Английская версия

См. описание по данной ссылке: [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
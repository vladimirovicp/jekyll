# jekyll

https://rubyinstaller.org - Ruby 3.4.2-1 (x64)

cmd

```
ruby -v
gem -v
```

Добавь сертификат
D:\Ruby34-x64\cacert.pem
set SSL_CERT_FILE=D:\Ruby34-x64\cacert.pem

```
ridk install
make -v
```

## Переменные

```
sysdm.cpl
дополнительно
переменные среды
D:\msys64\usr\bin
```

Bundler — это менеджер зависимостей для Ruby

```
gem install bundler
```

Установите Jekyll через Bundler

```
gem install jekyll
```

```
jekyll -v
```

## расширение

> Ruby (расширение для поддержки Ruby).
> Liquid (расширение для поддержки Liquid, языка шаблонов Jekyll).
> Markdown All in One (для работы с Markdown).
> Prettier (для форматирования кода).

## Проект

```
jekyll new my-site
jekyll new .
```

## Запуск локального сервера

```
bundle exec jekyll serve
```

## путь

http://localhost:4000/

## Обновить и перезапустить сайт

```
    bundle update
    bundle exec jekyll serve
```

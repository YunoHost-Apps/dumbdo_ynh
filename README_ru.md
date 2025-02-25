<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# DumbDo для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/dumbdo)](https://ci-apps.yunohost.org/ci/apps/dumbdo/)
![Состояние работы](https://apps.yunohost.org/badge/state/dumbdo)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/dumbdo)

[![Установите DumbDo с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdo)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить DumbDo быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A stupidly simple todo list application that just works. No complex database, no unnecessary features - just todos.

### Features

- Clean, minimal interface
- Dark/Light mode with system preference detection
- File-based storage - todos persist between sessions
- Fully responsive design
- Fast and lightweight
- PIN protection (4-10 digits if enabled)


**Поставляемая версия:** 1.0.0~ynh1

## Снимки экрана

![Снимок экрана DumbDo](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.dumbware.io/>
- Репозиторий кода главной ветки приложения: <https://github.com/DumbWareio/DumbDo>
- Магазин YunoHost: <https://apps.yunohost.org/app/dumbdo>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/dumbdo_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing --debug
или
sudo yunohost app upgrade dumbdo -u https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>

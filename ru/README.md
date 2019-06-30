## Переводы

Этот сайт доступен на следующих языках:

* [Английский](/)
* Русский

<h2 id="description">Описание</h2>

pgmig - это технология миграций СУБД postgresql, которая включает способ организации и загрузки в БД определений (DDL) и хранимого кода.

### Состав проекта

* [pgmig](https://github.com/pgmig/pgmig) - встраиваемая библиотека и утилита для миграции (golang)
* [pgmig.perl](https://github.com/pgmig/pgmig.perl) - порт pgmig на perl
* [`pgmig-*`](https://github.com/pgmig?q=pgmig-*) - пакеты дополнительного функционала:
  * [pkg] - управление пакетами и зависимостями
  * [testing](https://github.com/pgmig/pgmig-testing) - поддержка тестов
  * [testing-xml] - поддержка тестов для функций, которые возвращают xml
  * [rpc] - реализация RPC для проекта [apisite]()
  * [enfist] - пример хранимого кода, проект [enfist]()

## Технические детали

**В разработке**

## История

* Первая версия этой техники была реализована в 2010 как часть проекта [PgWS](https://github.com/LeKovr/pgws)
* Второе поколение - [pomasql](https://github.com/pomasql)
* Эта документация описывает третье поколение

## Авторы

* **Алексей Коврижкин** - *Идея и первичная реализация* - [LeKovr](https://github.com/LeKovr)

См. Также список [контрибьюторов](https://github.com/pomasql/poma/graphs/contributors), которые принимали участие в проекте.

## Лицензия

Исходный код проектов pgmig публикуется под лицензией Apache 2.0 - см файл [LICENSE.md](https://github.com/pgmig/pgmig/blob/master/LICENSE).

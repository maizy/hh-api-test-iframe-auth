# Тест авторизации в HH для приложения в iframe

Показывает, как успешно авторизовать в HeadHunter oauth,
при работе конечного приложения в iframe.


Для теста запустить два вебсервера для доменов:

* mydomain.example.org
* external.example.com

Прописав в hosts, что-то типа:

```
127.0.0.1 mydomain.example.org external.example.com
```

Пример конфига для nginx в `test-domains-nginx.conf`.



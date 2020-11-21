# DisableWebSearch
В Windows Search имеется баг, когда результаты веб-поиска отображаются некорректно:

![](https://github.com/ivanovskii/DisableWebSearch/blob/main/static/1.jpg)

Для отключения веб-поиска в Windows Search запустите файла внесения изменений в реестр `OFF_WebSearch_in_WindowsSearch.reg` и перезагрузите систему. Получим следующие результаты:

![](https://github.com/ivanovskii/DisableWebSearch/blob/main/static/2.jpg)

Баг был замечен на версии Windows 20H2 и старше после установки системы.
Для отката изменений запустите `ON_WebSearch_in_WindowsSearch.reg`

# DisableWebSearch
В Windows Search имеется баг, когда результаты веб-поиска отображаются некорректно:

<img width="550" src="static/1.jpg">

Для полного отключения веб-поиска в Windows Search запустите файла внесения изменений в реестр `OFF_WebSearch_in_WindowsSearch.reg`. Результат:

<img width="550" src="static/2.jpg">

Баг был замечен на версии Windows 20H2 и старше после установки системы.
Для отката изменений запустите `ON_WebSearch_in_WindowsSearch.reg`

# Content Flow

Официальная страница выпусков **Content Flow** для Windows.

## Скачать

Последняя версия находится на странице [Releases](https://github.com/rew8tuyghnwe4outihj/content-flow-releases/releases/latest). Скачивайте файл `ContentFlow-Setup-<версия>.exe`.

## Проверить файл

Каждый релиз содержит `SHA256SUMS.txt`. После загрузки можно проверить установщик командой PowerShell:

```powershell
Get-FileHash .\ContentFlow-Setup-3.4.0.exe -Algorithm SHA256
```

Полученный хеш должен полностью совпасть со значением из `SHA256SUMS.txt`.

## Важно

Установщик версии 3.4.0 пока не подписан доверенным сертификатом издателя, поэтому Windows SmartScreen может показать предупреждение. Не отключайте SmartScreen глобально и скачивайте программу только с этой страницы.

В этом репозитории нет пользовательской базы, фотографий, сессии WhatsApp, настроек или других личных данных.
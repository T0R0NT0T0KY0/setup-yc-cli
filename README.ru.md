# Подготовка последней версии Yandex Cloud CLI

## Переменные

* `SA_KEY` - Закрытый ключ вашего сервисного аккаунта (формат JSON) [необязательно]
* `FOLDER_ID` - [Идентификатор папки](https://yandex.cloud/en/docs/resource-manager/operations/folder/get-id?utm_referrer=https%3A%2F%2Fduckduckgo.com%2F) сервисного аккаунта (формат строка) [optional]

## Использование

см. [action.yml](action.yml)

```yaml
- name: Install Yandex CLI and Login
  uses: T0R0NT0T0KY0/setup-yc-cli@v1
  with:
    SA_KEY: ${{ secrets.YC_SA_KEY }}
    FOLDER_ID: ${{ secrets.YC_FOLDER_ID }}
```

Устанавливает последнюю версию Yandex Cloud CLI. Выполняет логин если указан SA_KEY.

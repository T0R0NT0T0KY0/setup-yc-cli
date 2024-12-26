# Подготовка последней версии Yandex Cloud CLI

## Использование

см. [action.yml](action.yml)

```yaml
- uses: T0R0NT0T0KY0/setup-yc-cli@v1
  with:
    # Закрытый ключ вашего сервисного аккаунта (формат JSON) [необязательно]
    SA_KEY: ${{ secrets.YC_SA_KEY }}

```

Устанавливает последнюю версию Yandex Cloud CLI. Выполняет логин если указан SA_KEY.

# Подготовка последней версии Yandex Cloud CLI

## Переменные

* `SA_KEY` - Your service account private key (json form) [optional]

## Использование

см. [action.yml](action.yml)

```yaml
- name: Install Yandex CLI and Login
  uses: T0R0NT0T0KY0/setup-yc-cli@v1
  with:
    SA_KEY: ${{ secrets.YC_SA_KEY }}

```

Устанавливает последнюю версию Yandex Cloud CLI. Выполняет логин если указан SA_KEY.

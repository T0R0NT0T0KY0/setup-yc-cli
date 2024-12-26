# Setup the latest version of Yandex Cloud CLI

## Inputs

* `SA_KEY` - Your service account private key (json form) [optional]

## Usage

See [action.yml](action.yml)

```yaml
- name: Install Yandex CLI and Login
  uses: T0R0NT0T0KY0/setup-yc-cli@v1
  with:
    SA_KEY: ${{ secrets.YC_SA_KEY }}

```

This will install the latest version of Yandex Cloud CLI. Then logging in if SA_KEY parameter is provided.

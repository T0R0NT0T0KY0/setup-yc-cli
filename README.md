# Setup the latest version of Yandex Cloud CLI

## Usage

See [action.yml](action.yml)

```yaml
- uses: T0R0NT0T0KY0/setup-yc-cli@v1
  with:
    # Your service account private key (json form) [optional]
    SA_KEY: ${{ secrets.YC_SA_KEY }}

```

***(eng)*** This will install the latest version of Yandex Cloud CLI. Then logging in if SA_KEY parameter is provided.

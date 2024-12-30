# Setup the latest version of Yandex Cloud CLI

## Inputs

* `SA_KEY` - Your service account private key (json form) [optional]
* `FOLDER_ID` - Your service account [folder id](https://yandex.cloud/en/docs/resource-manager/operations/folder/get-id?utm_referrer=https%3A%2F%2Fduckduckgo.com%2F) (string form) [optional]

## Usage

See [action.yml](action.yml)

```yaml
- name: Install Yandex CLI and Login
  uses: T0R0NT0T0KY0/setup-yc-cli@v1
  with:
    SA_KEY: ${{ secrets.YC_SA_KEY }}
    FOLDER_ID: ${{ secrets.YC_FOLDER_ID }}
```

This will install the latest version of Yandex Cloud CLI. Then logging in if SA_KEY parameter is provided.

## Update version

For example, version `v1.0.0` is used.

```shell
git tag v1.0.0
git push origin v1.0.0
git tag -f v1 v1.0.0
git push -f origin v1
```

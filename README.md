# npmrc-github-action

This action adds auth token for private npm registries to the `.npmrc` file.

## Inputs

### `token`

**Required** Access Token (scope depends on the type of registry).

### `registryUrl`

**Required** Url of your registry (without `https://`).

## Example usage
```
uses: digitalvisioncz/npmrc-github-action
with:
  token: '***'
  registryUrl: 'npm.pkg.github.com'
```
# yarn-registry-token-github-action

This action runs yarn after login into the private registry.

## Inputs

### `token`

**Required** Access Token (scope depends on the type of registry).

### `registryUrl`

**Required** Url of your registry (without `https://`).

### `registryName`

**Required** Name of your registry, usually your organization name.

## Example usage
```
uses: actions/yarn-github-package
with:
  token: '***'
  registryUrl: 'npm.pkg.github.com'
  registryName: '@digitalvisioncz'
```
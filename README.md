# JSON config action

This action load or set variable to JSON file.

## Inputs

## `operation`

**Required** Types of operation between "set" or "get".

## `filePath`

**Required** JSON config file location.

## `image`

**Required** Docker image tag.

## Outputs

## `result`

Retrieved variable.

## Example usage
```
uses: actions/json-config-action@v1.0
with:
  operation: 'set'
  filePath: '/file/config.json'
  image: 'docker.io/some-service'
```
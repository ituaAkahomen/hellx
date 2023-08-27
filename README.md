# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `greet-who`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `name`

Your name

### `time`

The time we greeted you.

## Example usage

```yaml
uses: itAkahomen/hello-x@0.1
with:
  who-to-greet: 'Captain Babarosa'
```

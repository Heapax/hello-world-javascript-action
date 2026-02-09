# Hello world JavaScript action

This action prints "Hello World" or "Hello" + the name of the person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@1a2b3c4d5e6f7a8b9c0d1e2f3a4b5c6d7e8f9a0b
with:
  who-to-greet: Shon the Megalodon
```
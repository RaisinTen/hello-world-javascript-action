![.github/workflows/main.yml](https://github.com/RaisinTen/hello-world-javascript-action/workflows/.github/workflows/main.yml/badge.svg)

# Hello world javascript action

THis action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@v1
with:
    who-to-greet: 'Mona the Octocat'
```

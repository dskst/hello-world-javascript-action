# hello-world-javascript-action

This is just test at GitHub Actions.
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

Link https://help.github.com/ja/actions/automating-your-workflow-with-github-actions/creating-a-javascript-action

## Inputs

### `who-to-greet`

**Required** The name of the persion to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'


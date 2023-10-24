# Snapshot report for `test/node-arguments/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://avajs.dev).

## passed node arguments to workers

> tests pass

    [
      {
        file: 'node-arguments.js',
        title: 'exec arguments includes --throw-deprecation',
      },
    ]

## detects incomplete --node-arguments

> fails with message

    'Could not parse `--node-arguments` value. Make sure all strings are closed and backslashes are used correctly.'

## reads node arguments from config

> tests pass

    [
      {
        file: 'node-arguments-from-config.js',
        title: 'works',
      },
    ]
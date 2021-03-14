# haskell-workbench




# Tooling notes

## Structure

Use `stack` for everything, write each file under `/src` then invoke from `/app/main.hs`.

`stack ghci` => REPL


Setup VS code's code-runner
```json
 "code-runner.executorMapByFileExtension": {
        ".hs": "stack runhaskell",
        }
```
# haskell-workbench

# Batteries
<https://hackage.haskell.org/packages/top>
+ lens

# Reference

+ prelude (base) library <https://hackage.haskell.org/package/base>

# Tooling notes

## Structure

`stack runghc ./nice.hs` -> run single file

### NO

Use `stack` for everything, write each file under `/src` then invoke from `/app/main.hs`.

`stack ghci` => REPL


Setup VS code's code-runner
```json
 "code-runner.executorMapByFileExtension": {
        ".hs": "stack runhaskell",
        }
```
[![stack](https://github.com/haskell-game-archives/haskell-tetris/workflows/stack/badge.svg)](https://github.com/haskell-game-archives/haskell-tetris/actions?query=workflow%3Astack)
[![cabal](https://github.com/haskell-game-archives/haskell-tetris/workflows/cabal/badge.svg)](https://github.com/haskell-game-archives/haskell-tetris/actions?query=workflow%3Acabal)
[![lint](https://github.com/haskell-game-archives/haskell-tetris/workflows/lint/badge.svg)](https://github.com/haskell-game-archives/haskell-tetris/actions?query=workflow%3Alint)
[![format](https://github.com/haskell-game-archives/haskell-tetris/workflows/format/badge.svg)](https://github.com/haskell-game-archives/haskell-tetris/actions?query=workflow%3Aformat)

# Building and running

## On Haskell Platform / with `cabal`

Building:
```shell
cabal configure
cabal install --only-dependencies
cabal build
```
Running:
```shell
cabal configure
cabal install --only-dependencies
cabal run
```

## With `stack`

Building:
```shell
stack build
```
Running:
```shell
stack exec htetris
```

# Screenshots
![](https://cloud.githubusercontent.com/assets/2439255/12403317/7e641ca0-be33-11e5-8d98-8b2afffe3720.png)
![](https://cloud.githubusercontent.com/assets/2439255/12403413/f6a1c0fa-be33-11e5-8770-41fb4a468b41.png)

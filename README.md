![stack](https://github.com/haskell-game-archives/haskell-tetris/workflows/stack/badge.svg)
![cabal](https://github.com/haskell-game-archives/haskell-tetris/workflows/cabal/badge.svg)

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

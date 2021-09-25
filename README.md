# tictactoe

[![CI](https://github.com/guerinoni/tictactoe/actions/workflows/CI.yml/badge.svg)](https://github.com/guerinoni/tictactoe/actions/workflows/CI.yml)

Game of tic tac toe with a strong AI.

Suuport for Linux and macOS.

![](./docs/screenshot.png)

## Build

```bash
git clone git@github.com:guerinoni/tictactoe.git
cd tictactoe
mkdir build
cd build
cmake ..
cmake -build .

# if you want run tests
ctest
```


## Contributing

1. Any kind of help is welcome (issue, comment, request, PR...).
2. Make sure to run `./scripts/clang-format.sh` before PR.
3. Enjoy.
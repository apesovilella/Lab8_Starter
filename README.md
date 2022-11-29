# Lab 8 - Starter

## 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

- Within a Github action that runs whenever code is pushed, because this way we ensure at every step of development that the code works and follows all the quality requirements. If a branch would merge with main in Github without checking the code, many problems would arise and the testing at the end could become a bigger problem than the project itself.

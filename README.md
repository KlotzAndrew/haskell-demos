```shell
ghc -o hello hello.hs
./hello

ghc -O2 --make par.hs -threaded -rtsopts
time ./par +RTS -N2
```

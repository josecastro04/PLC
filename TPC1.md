# TPC1

#### Expressão regular para apanhar strings binárias que não contenham a substring "011"
---

```
^1*(0|01)*$
```

##### Exemplos
```
011011
10111
1101 (Aceite)
101010 (Aceite)
000000000000 (Aceite)
111111111111 (Aceite)
110101000000 (Aceite)
```

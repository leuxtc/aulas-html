## box-sizing

o ```box-sizing``` é uma propriedade CSS que define como a proporção de um elemento será calculado.


### Como é calculado:
```
    width = largura + borda + padding
```
___

### content-box:

```
    width = 200px
    height = 200px

    margin = 20px
    padding = 20px

    200px + 20px + 0 + 20px = 240px
```

O ```content-box``` será calculado de forma somatoria

___
### border-box:

```
    width = 200px
    height = 200px

    margin = 20px
    padding = 20px

    160px + 20px + 0 + 20px = 200px
``` 

Ja o ```border-box``` é calculado para que o total da soma continue respeitando o tamanho original
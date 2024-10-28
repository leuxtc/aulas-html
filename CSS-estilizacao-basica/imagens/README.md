## Object-fit | Object-position

São formas de definir como **imagens** irão se comportar em um determinado campo

### Object-fit

O ```object-fit:``` determina como aquela **imagem** irá preencher aquele local que está inserida por alguns valores:

|    |    |
|----|----|
```fill``` | valor padrão, preencherá todo o espaço deformando a imagem para que caiba
```contain``` | manterá a qualidade da imagem porém sem preencher todo o espaço
```cover``` | cobrirá todo espaço sem deformar a imagem
```scale-down``` | escolherá entre none ou contain para caber no espaço
```none``` | manterá o tamanho original da imagem 
|   |    |

### Object-position

Já o ```object-position``` será para mudar a **posição** da **imagem** dentro do espaço inserido, pode ser definido com os valores:

|    |    |
|----|----|
```porcentagem``` | define por porcentagem de 0% a 100% o ``x`` e o ``y`` da imagem
```nome da posição``` | define pelo nome da posição, sendo: ``center``, ``left``, ``right``, ``bottom``, ``top``, ``start``, ``end``
```pixels``` | define o ``x`` e o ``y`` respectivamente pelo valor em pixels: 10px 30px;
|   |    |
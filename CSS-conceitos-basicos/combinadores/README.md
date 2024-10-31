## Combinadores

**Combinadores** são formas de chamar ou agrupar elementos para modificar de uma vez só mais de um elemento

___

### Agrupamento

O **agrupamento** é usado com uma ```,``` depois das propriedades, ira modificar todos elementos que estão agrupados

```css
    h1, p, div {
        ...
    }
```

### Descendente

Esse é um modo de chamar **elementos** que estão dentro de outros **elementos** de forma descendente da esquerda para direita apenas com **espaço**

```css
    div span p {
        ...
    }

    <div>
        <span>
            <p>...<p> //apenas esse será modificado
        </span>
    </div>
```

### Filho

Chama **elementos filhos** também de forma descendente com o combinador ```>```

```css
    div > span {
        ...
    }

    <div>
        <span> //apenas esse será modificado
            <p>...</p>
        </span>
    </div>
```

### Irmao

Chama por **elementos irmãos** que são elementos que vão estar proximos de tags no sentido de cima pra baixo com o combinador ```+```

```css
    div p + p {
        ...
    }

    <div>
        <p>...</p> 
        <p>...</p> //esse será modificado
        <p>...</p> //esse será modificado
    </div>
```

no código ```div p + p``` estamos buscando dentro da ```<div>``` todos elementos irmãos de ``<p>``, o primeiro ```<p>``` não será modificado porque ele **não** é **irmão**, ele apenas tem um **irmão**
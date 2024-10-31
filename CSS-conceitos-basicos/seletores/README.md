## Seletores

Seletores são formas de instanciar algum elemento do HTML, é possível instanciar por formas como: 
```<tag>```
```[atributo=""]```
```class=""```
```id=""```
``` * ```

### ```<tag>```:

Esse seletor é usado para chamar por meio de ```<tags>```. Ele vai personalizar todas as ```<tags>``` que tiverem no HTML

```css
    h1 {
        ...
    }

    <h1>...</h1>
```

### ```class=""```:

Esse é um modo que chama de forma genérica elementos através de um atributo ```class=""``` usando o seletor ```.```
```css
    .classe {
        ...
    }

    <h1 class="classe">...</h1>
```

### ```id=""```:

Esse é um seletor que chama de forma única um elemento usando o atributo ```id=""``` com o seletor ```#```

```css
    #identificador {
        ...
    }

    <h1 id="identificador">...</h1>
```

### ```*```:

Esse seletor chama todos os elementos dentro de um HTML

```css
    * {
        ...
    }

    <h1>...</h1>
    <p>...</p>
```

### ```[atributo=""]```:

Essa forma serve para chamar atráves de um **valor** de um **atributo**

```css
    [title="paragrafo"] {
        ...
    }

    <h1 title="titulo-pagina">...</h1>
    <p title="paragrafo">...</p>
```

Esse seletor tem algumas formas de se instanciar um valor:

|seletor|resumo|
|-------|-------|
|```=```|  seletor padrão que procura um valor igual ao colocado e único  |
|```~=```|  seletor que pode ser um valor que esteja em qualquer lugar do atributo ou com mais valores  |
|```^=```|  seletor usado para préfixos, procura valores que aparecem antes de outros  |
|```$=```|  seletor para pósfixos, procura valores que aparecem no final do atributo  |
|```*=```|  procura por qualquer área do valor do atributo  |
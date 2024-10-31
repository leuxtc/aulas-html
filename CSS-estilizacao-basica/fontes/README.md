## Fonte

É possível configurar e personalizar as **fontes** que irão aparecer na página HTML através de diversas propriedades:

| Tipo  |  Resumo  |
|-------|----------|
|``font`` | short-hand para todas proximas propriedades |
|``font-size`` | define o tamanho da fonte |
|``font-style`` | define o estilo da fonte (normal, *italic*, *oblique*) |
|``font-weight`` | define a grossura da fonte (deixar em **negrito**) |
|``font-variant`` | deixa a fonte em ``small-caps`` |

As fontes são definidas apenas escrevendo seu **nome** e também é possível definir "**reservas**"  adicionando virgulas caso a fonte principal não funcione

```css
    div {
        font-family: 'Arial', 'Helvetica', 'Times New Roman';
    }
```

### Line-height

Define o tamanho do espaçamento das linhas **multiplicando** o valor colocado da propriedade com o **tamanho da fonte**

```css
    p {
        font-size: 20px;
        line-height: 2;
    }

    // O line-height será de 40
```

### Importar fontes

Também é possível **importar** outras fontes personalizadas de sites como por exemplo o

[/fonts.google.com](fonts.google.com)

A **importação** pode ser feita através do ``<link>`` ou do ``@import`` que podem ser encontrados no próprio [fonts.google.com](fonts.google.com)

Link:

```html
    <link rel="preconnect" href="https://fonts.googleapis.com">

    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
```

// Esse modo vai no head do HTML

Import:

```css
    @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap')
```

// Esse modo pode ser colocado diretamente no CSS ou também no head do HTML com a tag ``<style>``
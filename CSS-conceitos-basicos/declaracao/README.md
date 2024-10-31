## Modos de declaração CSS

### CSS Inline

O **<u>CSS Inline</u>** é a forma de declaração que acontece dentro das próprias tags HTML. Não é muito indicada pois é menos versátil e mais trabalhosa de se usar.

```
<h1 style="background: red; color: white;">...</h1>
```

### CSS Interno

O **<u>CSS Interno</u>** é uma declaração um pouco mais utilizavel, ela funciona com uma tag (```<style>```) dentro do head do arquivo HTML

```css
<style>
    h1 {
        background-color: red;
        color: white;
    }
    
    h2 {
        color: red;
    }
</style>
```

### CSS Externo

O **<u>CSS Externo</u>** é a forma mais utilizada e indicada para se declarar um CSS, ela funciona como um arquivo externo **.css** separado, que pode ser usado e reutilizado aonde você quiser pela tag ```<link>```

| exemplo/index.html:
```html

<link rel="stylesheet" href="exemplo/css/style.css">

```

| exemplo/css/style.css:
```css
h1 {
    background-color: red;
    color: white;
}

h2 {
    color: red;
}
```

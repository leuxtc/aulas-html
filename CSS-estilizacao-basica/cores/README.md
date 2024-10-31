## Cores

No CSS há varias formas de se colorir **elementos** usando a propriedade ```color```, elas são: 

```pré-definição``` ```hexadecimal``` ```RGB``` ```HSL```

### Pré-definição

É a forma que se usa apenas o **nome da cor**. O CSS possui cerca de **141 cores** ja pré-definidas que podem ser usadas apenas pelo seu nome

```
    color: red;
```
[Todas as cores pré-definidas](https://www.w3schools.com/w3css/w3css_colors.asp)

___

### Hexadecimal

É a forma para colorir usando o código hexadecimal de 6 dígitos por meio do ``#``,  sendo: 

```css
    # 00          00       00
     vermelho    azul     verde

    color: #ff0000; 
    
    //cor vermelha
```

Adicinando mais 2 dígitos no código **hexadecimal**, é possível mudar sua **transparência**.

```css
    # 00          00       00        00
     vermelho    azul     verde     alpha

    color: #00ff0050; 
    
    //cor azul com transparência de 50%
```

___

### RGB | RGBA

São formas mais diretas de mistura de cor usando a propriedade ```rgb()``` tendo valores de 0 a 255 para cada cor

```css
    rgb(RED, GREEN, BLUE)

    color: rgb(255, 255, 0); 
    
    //cor amarela
```

O ```rgba()``` é a mesma coisa porém com adicional do canal ```alpha``` (transparência) que funciona de 0 a 1, sendo 1 o 100%

```css
    rgb(RED, GREEN, BLUE)

    color: rgb(255, 255, 0, 0.5); 
    
    //cor amarela com 50% de transparência
```

___

### HSL | HSLA

O **HSL(Hue, Saturation, Lightness)** é usado com a propriedade ```hsl()```, e serve para ter um controle da saturação da cor e da sua luminosidade

- **HUE (matiz):** é o grau na roda de cores (0 a 360 graus)
    - 0 ou 360 é vermelho
    - 120 é verde
    - 240 é azul
- **Saturation (saturação):** valor percentual
    - 0% um tom de cinza
    - 100% cor total
- **Lightness (luminosidade):** luminosidade da cor
    - 0% é preto
    - 50% valor padrão
    - 100% é branco

```css
    color: hsl(240, 100%, 50%); 
    
    //cor azul com sua saturação em 100% e sua porcentagem de 50% padrão
```

Ja o **HSLA(Hue, Saturation, Lightness, Alpha)** é a mesma coisa porém com seu canal de **transparência**(``alpha``)

```css
    h1 {
        color: hsla(0, 100%, 50%, 1); 
    }
    
    // cor vermelha com sua saturação em 100%, sua luminosidade padrão de 50% e 100% de transparência
```
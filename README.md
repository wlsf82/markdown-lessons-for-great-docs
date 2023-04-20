# Lições de markdown para ótimas documentações

## h2

Parágrafo exemplo...

### h3

Exemplo do código **JavaScript** com múltiplas linhas abaixo.

```js
// greatting.js

const name = 'Walmyr'

console.log(`Olá ${name}`)

/*
 * Multiple
 * Lines
 * JS
 * Comment
 */

```

Exemplo de código **shell** com múltiplas linhas abaixo.

```sh
pwd
mkdir example/
cd example/
git init
npm init -y

```

Exemplo de código **Ruby** com múltiplas linhas abaixo.

```rb
# sum.rb

def sum(a, b)
  a+b
end

```

Exemplo de código _inline_ a seguir: `npm install example -S`.

## Listagem não-numerada

- Foo
- Bar
- Baz


### Listagem não-numerada com identação

- Foo
- Bar
- Baz
  - Bah
  - Bãeih

## Listagem numerada

1. Item 1
2. Item 2
3. Item 3


### Listagem numerada com identação

1. Item 1
2. Item 2
3. Item 3
    1. Item a
    2. Item b
4. Item 4

## Outro h2

Exemplo de <kbd>Botão</kbd>.


## _Expandable and collapsible_

<details>
  <summary>Abra para ver mais detalhes</summary>
  <br>

Informação detalhada aqui.

Blablabla.

...
</details>

## Citações (_Quotes_)

### Uma linha

> Como as pessoas tratam você é o karma delas; como você reage é o seu. Wayne Dyers

### Múltiplas linhas

> Como as pessoas tratam você é o karma delas; como você reage é o seu.
>
> Wayne Dyers

### Blocos de citação aninhados

> Dorothy a seguiu por muitos dos belos aposentos de seu castelo.
>
>> A Bruxa ordenou que ela limpasse as panelas e chaleiras, varresse o chão e mantivesse o fogo alimentado com lenha.

### Blocos de citação com outros elementos

> #### Os resultados do último trimestre parecem ótimos!
>
> - Receita
> - Lucro
>
> _Tudo_ está de acordo com os **planos**.

## Imagens

![Tux, o mascote do Linux](./assets/images/tux.avif)

___

Feito com 💛 por [Walmyr Filho](https://walmyr.dev).

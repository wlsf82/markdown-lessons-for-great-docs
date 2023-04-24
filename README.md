# Lições de _Markdown_ para ótimas documentações

## h2

Parágrafo exemplo...

### h3

Exemplo de bloco de código sem definição da linguagem com múltiplas linhas abaixo.

```
{
  "name": "walmyr",
  "nationality": "brazilian",
  "maried": true
}

```

Exemplo de **json** com múltiplas linhas abaixo.

```json
{
  "name": "walmyr",
  "nationality": "brazilian",
  "maried": true
}

```

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


### Listagem não-numerada com recuo

- Foo
- Bar
- Baz
  - Bah
  - Bãeih

## Listagem numerada

1. Item 1
2. Item 2
3. Item 3


### Listagem numerada com recuo

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

### Múltiplas linhas abaixo

> Não contavam com minha astúcia!
>
> Chapolin Colorado

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

## Checkboxes

- [x] Estudar HTML
- [x] Estudar CSS
- [x] Estudar JavaScript
- [ ] Estudar Cypress
  - [x] Testes de GUI
  - [x] Testes de API
  - [ ] Testes de Componentes

## Tabelas

| ID     | isAvailable | stockQty |
| -------| ----------- | -------- |
| 00001  | true        | 257      |
| 00002  | false       | 0        |

## _Strikethrough_

Use Cypress ~~com _Cucumber_ e _Page Objects_~~ utilizando sua estrutura padrão.

## Links

### Automático

https://example.com

### Desabilitado

`https://example.com`

___

Feito com 💛 por [Walmyr](https://walmyr.dev).

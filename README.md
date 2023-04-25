# Lições de _Markdown_ para ótimas documentações

## h2

Parágrafo exemplo...

### h3

#### h4

##### h5

###### h6

Exemplo de bloco de código sem definição de linguagem com múltiplas linhas.

```
{
  "name": "Walmyr",
  "nationality": "Brazilian",
  "maried": true
}

```

Exemplo de bloco de código **JSON** com múltiplas linhas.

```json
{
  "name": "Walmyr",
  "nationality": "Brazilian",
  "maried": true
}

```

Exemplo de bloco de código **HTML** com múltiplas linhas.

```html
<!-- index.html -->

<!DOCTYPE html>
<html lang="PT-BR">
  <head>
    <title>Aplicação Exemplo</title>
  </head>
  <body>
    <h1>Título exemplo</h1>
    <p>Parágrafo exemplo</p>
  </body>
</html>

```

Exemplo de bloco de código **JavaScript** com múltiplas linhas.

```js
// greetings.js

const name = 'Walmyr'

console.log(`Olá ${name}!`)

/*
 * Multiple
 * Lines
 * JS
 * Comment
 */

```

Exemplo de bloco de código **shell** com múltiplas linhas.

```sh
pwd
mkdir example/
cd example/
git init
npm init -y

```

Exemplo de bloco de código **Ruby** com múltiplas linhas.

```rb
# sum.rb

def sum(a, b)
  a+b
end

```

Exemplo de código _inline_ a seguir: `npm install example -S`

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

Exemplo de <kbd>botão</kbd>.

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

> Não contavam com minha astúcia!
>
> Chapolin Colorado

### Blocos de citação aninhados

> Dorothy a seguiu por muitos dos belos aposentos de seu castelo.
>
>> A Bruxa ordenou que ela limpasse as panelas e chaleiras, varresse o chão e mantivesse o fogo alimentado com lenha.

### Bloco de citação com outros elementos

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

| ID     | isAvailable | stockQty  |
| ------ | ----------- | --------- |
| 00001  | true        | 257       |
| 00002  | false       | 0         |

## _Strikethrough_

Use Cypress ~~com Cucumber e _Page Objects_~~ utilizando sua estrutura padrão.

## Link

### Automático

https://example.com

### Desabilitado

`https://example.com`

___

Feito com 💚 por [Walmyr](https:walmyr.dev).

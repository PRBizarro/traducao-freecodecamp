---
id: 587d781c367417b2b2512ac2
title: Defina o tamanho da fonte (font-size) para múltiplos elementos de cabeçalho (heading)
challengeType: 0
videoUrl: 'https://scrimba.com/c/cPpQNT3'
forumTopicId: 301067
dashedName: set-the-font-size-for-multiple-heading-elements
---

# --description--

A propriedade `font-size`é usada para especificar o quão grande será o texto em um determinado elemento. Essa regra pode ser usado para múltiplos elementos para criar uma consistencia visual dos textos na página. Nesse desafio, você irá definir os valores das tags `h1` até `h6` para balancear os tamanhos dos cabeçalhos (heading).

# --instructions--

  <p>Nas tags do <code>style</code>, defina o <code>font-size</code> das tags:</p>

  <ul>
    <li><code>h1</code> para 68px.</li>
    <li><code>h2</code> para 52px.</li>
    <li><code>h3</code> para 40px.</li>
    <li><code>h4</code> para 32px.</li>
    <li><code>h5</code> para 21px.</li>
    <li><code>h6</code> para 14px.</li>
  </ul>

# --hints--

O seu código deve definir a propriedade `font-size` da tag `h1` para 68 pixels.

```js
assert($('h1').css('font-size') == '68px');
```

O seu código deve definir a propriedade `font-size` da tag `h2` para 52 pixels.

```js
assert($('h2').css('font-size') == '52px');
```

O seu código deve definir a propriedade `font-size` da tag `h3` para 40 pixels.

```js
assert($('h3').css('font-size') == '40px');
```

O seu código deve definir a propriedade `font-size` da tag `h4` para 32 pixels.

```js
assert($('h4').css('font-size') == '32px');
```

O seu código deve definir a propriedade `font-size` da tag `h5` para 21 pixels.

```js
assert($('h5').css('font-size') == '21px');
```

O seu código deve definir a propriedade `font-size` da tag `h6` para 14 pixels.

```js
const regex = /h6\s*\{\s*font-size\s*:\s*14px\s*(;\s*\}|\})/i;
assert.strictEqual(true, regex.test(code));
```

# --seed--

## --seed-contents--

```html
<style>




</style>
<h1>This is h1 text</h1>
<h2>This is h2 text</h2>
<h3>This is h3 text</h3>
<h4>This is h4 text</h4>
<h5>This is h5 text</h5>
<h6>This is h6 text</h6>
```

# --solutions--

```html
<style>
  h1 {
    font-size: 68px;
  }
  h2 {
    font-size: 52px;
  }
  h3 {
    font-size: 40px;
  }
  h4 {
    font-size: 32px;
  }
  h5 {
    font-size: 21px;
  }
  h6 {
    font-size: 14px;
  }
</style>
<h1>This is h1 text</h1>
<h2>This is h2 text</h2>
<h3>This is h3 text</h3>
<h4>This is h4 text</h4>
<h5>This is h5 text</h5>
<h6>This is h6 text</h6>
```

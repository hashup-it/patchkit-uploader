---
layout: page.11ty.cjs
title: <hashup-game-uploader> ⌲ Home
---

# &lt;my-element>

`<my-element>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<my-element>` is just an HTML element. You can it anywhere you can use HTML!

```html
<hashup-game-uploader></hashup-game-uploader>
```

  </div>
  <div>

<hashup-game-uploader></hashup-game-uploader>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<my-element>` can be configured with attributed in plain HTML.

```html
<hashup-game-uploader name="HTML"></hashup-game-uploader>
```

  </div>
  <div>

<my-element name="HTML"></my-element>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<my-element>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;my-element&gt;</h2>
    <hashup-game-uploader .name=${name}></hashup-game-uploader>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;my-element&gt;</h2>
<my-element name="lit-html"></my-element>

  </div>
</section>

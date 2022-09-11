# React typing effect text animation component 

A layout component to create a typewriter typing animation effect for text. 


## Installation

Run `npm i text-type-animation-effect-react` or `yarn add text-type-animation-effect-react` in the root of your React project


## Usage

In the component where you want to see the animation of typing effect import `TextTyper` with 

```js
import TextTyper from 'text-type-animation-effect-react'
```

Render passing the props with the text to type, interval (optional) and HTML element to use (optional):

```js
<TextTyper text={textToRender} interval={10} Markup={"code"} />
```

<img src='https://barcelonacodeschool.com/files/pics/text-type-animation-effect-react.gif' alt='A layout component to create a typewriter typing animation effect for text'/>

## Props

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Type</th>
    <th>Default</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>text</td>
    <td>string</td>
    <td>''</td>
    <td>String text value you want to print. The text which would be rendered with the typing animation effect</td>
  </tr>
  <tr>
    <td>interval</td>
    <td>number</td>
    <td>100</td>
    <td>Number in millisecond to control the speed of typing, delay between rendering each character in milliseconds</td>
  </tr>
  <tr>
    <td>Markaup</td>
    <td>string</td>
    <td>span</td>
    <td>Any valid HTML element to render your text within, like p, h1, span, code, etc...</td>
  </tr>
</tbody>
</table>

---

npm: https://www.npmjs.com/package/text-type-animation-effect-react

Done at <a href='https://barcelonacodeschool.com'>Barcelona Code School</a>
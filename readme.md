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

## Props



There are two props accepted: `columns` and `gap`

### `columns` accepted values: 

* a number -- in this case it will be the number of columns with the same width, example:

```js
<Grid columns={"2"} gap={'1em'}>
// will create 2 equally sized columns
<Grid columns={"5"} gap={'1em'}>
will create 5 equally sized columns
```

* several length units accepted in CSS -- in this case it will be width of corresponding columns, example:

```js
<Grid columns={"1fr 50% 200px"} gap={'1em'}>
// will create 3 columns with width 1fr for the first columns, 50% for the second column and 200px for the third column
```

### `gap` accepted values:

Any length unit which will be used as a gap between columns and rows of your grid.

---

Done at <a href='https://barcelonacodeschool.com'>Barcelona Code School</a> -->
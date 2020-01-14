# react-graph-visualizer

> a react component to visualize interactive directed and weighted graphs easily.

[![NPM](https://img.shields.io/npm/v/react-graph-visualizer.svg)](https://www.npmjs.com/package/react-graph-visualizer) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

 
## Install

```bash
npm install --save react-graph-visualizer
```
## Examples 
### gif 
### demo
the demo contains multiple code examples with their results.
### the debt settler app
the debt settler is react app made using the react-graph-visualizer.
## Usage

```jsx
import React, { Component } from 'react'

import Graph from 'react-graph-visualizer'

class Example extends Component {
  render () {
    return (
      <Graph />
    )
  }
}
```
## API 
| Prop         | Type          | Default  |Description|
| :------------- |:-------------| :-----|:----|
|initialGraph|object|``` {nodes:[],links:[]} ```|Graph initial data|
|initialGraph.nodes|Array |[]|The nodes array of objects ``` {name:”string”, id:”number”, img=’string’}``` |
|initialGraph.links|Array|[]|The links array of objects {source:”number”, target:’number’, label:”string”}|
|width|number|700|the vertical length of the component|
|height|number|500|the horizontal  length of the component|
|ref |Ref object||The ref object to use to change graph data|
|backgroundColor|string|#e5e6e7|The component background color|
|linkStyle.directed|boolean|true|Specifies the type of the graph directed or undirected|
|linkStyle.distance|number|300|The length of the links, or the distance between nodes|
|linkStyle.color|string|black|Links color: “red”, “orange”, “#000”, “#e5e6e7”|
|nodeStyle.radius|number|30|The radius of nodes|
|nodeStyle.borderWidth|numer|2|The nodes border width|
|nodeStyle.borderColor|string|black|
|The nodes border color|nodeStyle.background|string|black|The nodes background color|
|nameStyle.size|number|20|The nodes name size|
|nameStyle.color|string|black|The nodes name color|
|nameStyle.x|string|“center”|The nodes name horizontal position: left, right, center.|
|nameStyle.y|string|“bottom”|The nodes name vertical position: bottom, top.|
|labelStyle.show|boolean|false|Show or hide labels|
|labelStyle.size|number|10|The size of the labels|
|labelStyle.color|string|“black”|The color of the labels|








## License

MIT © [NadirTellai](https://github.com/NadirTellai)

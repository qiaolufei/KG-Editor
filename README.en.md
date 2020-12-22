English | [简体中文](README.md)

<h1 align="center">Knowledge-Graph Editor(KG-Editor)</h1>
<div align="center">

Visual knowledge graph editor based on [Vue 2.x](https://cn.vuejs.org/v2/guide/) +  [G6 3.8](https://g6.antv.vision/zh)  + [Vuetify](https://vuetifyjs.com/en/)

</div>

## Demo address

<div align="center">

[KG-Editor](http://175.24.122.85:1030/#/)

</div>

## Function introduction

- [x] Add node---Double-click the blank space of the canvas to add a node
- [x] Edit node---click the node to edit the node in the configurator on the right
- [x] Add connection---Move the mouse into the node to display the anchor point, click on the anchor point to be the starting node, click on other nodes to realize the connection
- [x] Edit connection---click the connection to edit the connection in the configurator on the right
- [x] Thumbnails---the right navigator implements thumbnails
- [x] Undo function (Revocation of adding or deleting nodes and connections)
  - [x] Click the button to cancel
  - [x] Ctrl + Z to undo
- [x] Redo function
- [x] Copy node function
  - [x] Click the button to copy
  - [x] Ctrl + C to copy
- [x] Paste node function
  - [x] Click the button to paste
  - [x] Ctrl + V to paste
- [x] Delete node, connection function
  - [x] Click the button to delete
  - [x] Ctrl + Backspace to delete
- [x] Bring to Front function
- [x] Bring to Back function
- [x] Enlarge the canvas function
  - [x] Click the button to enlarge
  - [x] Swipe up the mouse wheel
- [x] Reduce the canvas function
  - [x] Click the button to reduce
  - [x] Swipe down the mouse wheel
- [x] Adapt to the canvas
- [x] Upload data file to generate knowledge graph function

```js
// file data format
{
    "nodes":[
        {"id": "node1", "label": "luffy"},
        {"id": "node2", "label": "24岁"},
        {"id": "node3", "label": "62kg"}
        ...
    ],
    "edges":[
        {"source": "node1", "target": "node2", "label": "年龄"},
		{"source": "node1", "target": "node3", "label": "体重"}
        ...
    ]
}
```

- [x] Export picture function
- [x] Help

## Contact Me

#### Email: luffy0101@163.com
#### WeChat： 
![qlc0607](WeChat.jpg)
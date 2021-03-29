## Tiled

<br>

To create a teleport zone, create a new layer then set the property below in custom properties of this layer,
each tile drawed with the layer is a teleporter
``` json
{
    "name": "exitSceneUrl",
    "type": "string",
    "value": "path/of/my_map.json"
}
```
<br>

To set tile as a collider, set the property below in custom properties of a tile
``` json
{
    "name": "collides",
    "type": "bool",
    "value": true
}
```
<br>

To create a start point, create a layer named "start" then drawn least one tile.
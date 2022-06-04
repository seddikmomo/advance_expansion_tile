# Configurable Expansion

![configurable-expanion-tile](configurable_expansion_tile.gif)

1.  It allows you to manually collapse, exapnd or toggle expansion tile
2.  It allows you to hide the default icon
3.  It allows you to disable click of the exapnsion tile
4.  It provides the onTap callback whenever the expansion tile gets clicked

## Getting Started

### Exapnd, Collapse, Toggle Manually
To do so, you need to create global key first.
```
final GlobalKey<ConfiguarableExpansionTileState> _globalKey = GlobalKey();

///To exapnd 
_globalKey.currentState?.expand();

///To collapse
_globalKey.currentState?.collapse();

///To toggle
_globalKey.currentState?.toggle();
```

### Properties
```
/// use to hide the default trailing icon
bool hideIcon

///use to disable the click of the expansion tile
bool disabled

///use to listen click event once the expansion tile gets clicked.
VoidCallback onTap
```


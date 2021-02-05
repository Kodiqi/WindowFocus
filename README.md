# WindowFocus
Made to resolve a recent issue with HTML5 Gamemaker games losing focus, resulting in them not accepting keyboard input. Based on u/linkazoid fix posted on r/gamemaker

Added the extension, via Tools > Import Local Package, then use the WindowFocus function. For example...

```
// Step event
if (mouse_check_button(mb_any))	
  {
  WindowFocus();	
  }
```

Made and tested in 2.3.1

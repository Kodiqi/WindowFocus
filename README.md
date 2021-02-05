# WindowFocus
Small extension to return focus to HTML5 games made with Gamemaker

Made to resolve a recent issue with HTML5 Gamemaker games losing focus, resulting in them not accepting keyboard input.

Added the extension, via Tools > Import Local Package, then use the WindowFocus function. For example...

// Step event
```
if (mouse_check_button(mb_any))	
  {
  WindowFocus();	
  }
```

Made and tested in 2.3.1

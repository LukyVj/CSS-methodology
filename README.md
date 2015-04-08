# CSS-methodology
My own CSS guidelines &amp; methods
--- 

### Spacing 
#### CSS
```css
selector {
  property: value;
}

selector{
  property: value;
}
```
#### SASS
```css
selector {
  property: value;
  
  otherSelector {
    property: value;
  }
}
```

### Classing
#### CSS 
```css
element.class {
  property: value;
}

element.class-2 {
  property: value;
}
```

#### SASS
```css
element.class {
  property: value;
}

element{
  
  &.class-1{
    property: value;
  }
  
  &.class-2{
    property: value;
  }
}
```

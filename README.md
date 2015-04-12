# CSS-methodology
My own CSS guidelines &amp; methods
--- 

- [Intro](#intro)
- [Spaces](#spaces)
- [Classes](#classes)

### Intro

Howdy stranger ! 
Welcome to my CSS-Methodology index, I decided to create this index since CSS is what I prefer to write when I have some free time, I also get some questions about my coding styles & conventions.. So here they are. 

List will grow as much as possible, I'll fill it step by step with the time, so we can consider that it will never be "done"

----

### Spaces
#### CSS
```css
selector {
  property: value;
}

selector {
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

### Classes
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



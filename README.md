# CSS-methodology
My own CSS guidelines &amp; methods
--- 

- [Intro](#intro)
- [Spaces](#spaces)
- [Nesting](#nesting)
- [Classes](#classes)
- [Id](#id)

### Intro

Howdy stranger ! 
Welcome to my CSS-Methodology index, I decided to create this index since CSS is what I prefer to write when I have some free time, I also get some questions about my coding styles & conventions.. So here they are. 

Keep in mind that it will be a mix of CSS and SASS code examples.

List will grow as much as possible, I'll fill it step by step with the time, so we can consider that it will never be "done"

----

### Spaces
#### CSS
```css
selector{
  property: value;
}

selector otherselector{
  property: value;
}

selector,
selector,
selector{
  property: value;
}
```
#### SASS
```css
selector{
  property: value;
  
  otherselector{
    property: value;
  }
}

selector,
selector,
selector{
  property: value;
}
```

### Nesting
#### SASS
```css
selector{
  property: value;

  selector{
    property: value;

    slelector{
      property: value;

      &:hover{
        property: value;
      }
    }
  }
}
```

### Classes
#### CSS 
```css
element.class{
  property: value;
}

element.class-2{
  property: value;
}
```

#### SASS
```css
element.class{
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



### Id
#### CSS 
```css
#anId{
  property: value;
}
```

> Note that I only use ids when I have to use Javascript. I prefer target any triggers and targets with ids.

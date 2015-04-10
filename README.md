# CSS-methodology
My own CSS guidelines &amp; methods
--- 

### Spacing 
#### CSS
```css
selector {property: value;}

selector {
  property: value;
  property: value;
  /* and so on */
}

selector,
selector,
selector {
  property: value;
}
```

### Classing
#### CSS 
I'm using the [BEM](https://en.bem.info/) methodology with its default syntax. 
```css
.block {
  property: value;
}

.block__element {
  property: value;
}

.block__element--modifier {
  property: value;
}
```

#### SASS
```css
.block {
  property: value;
  &__element {
    property: value;
    &--modifier {
      property: value;
    }
  }
}
```
I try to avoid to nest more than 3 elements.
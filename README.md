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
  property: value;
  /* and so on... */
}

selector,
selector {
  property: value;
}

selector,
selector {
  property: value;
  property: value;
  /* and so on... */
}
```

### Classing
#### CSS 
I use, and recommend, [BEM](https://en.bem.info/) methodology.
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
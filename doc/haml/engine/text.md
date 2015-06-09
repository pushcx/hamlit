# [text\_spec.rb:15](/spec/hamlit/engine/text_spec.rb#L15)
## Input
```haml
.
.*
#
#+

```

## Output
### Haml
```html
Haml::SyntaxError: Illegal element: classes and ids must have values.
```

### Hamlit
```html
.
.*
#
#+

```


# [text\_spec.rb:114](/spec/hamlit/engine/text_spec.rb#L114)
## Input
```haml
&nbsp;
\&nbsp;
!hello
\!hello

```

## Output
### Haml
```html
&nbsp;
&nbsp;
!hello
!hello

```

### Hamlit
```html
nbsp;
&nbsp;
hello
!hello

```

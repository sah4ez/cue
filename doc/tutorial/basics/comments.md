[TOC](Readme.md) [Prev](foldany.md) [Next](numberlit.md)

_JSON Sugar and other Goodness_

# Comments

CUE supports C-style block and line comments.

<!-- CUE editor -->
_comments.cue:_
```
// whole numbers
one: 1
two: 2

/* fractions
 */
"two-and-a-half": 2.5
```

<!-- JSON result -->
`$ cue export comments.cue`
```json
{
    "one": 1,
    "two": 2,
    "two-and-a-half": 2.5
}
```
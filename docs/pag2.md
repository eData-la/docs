---
title: titi
---

# Ejemplos

## Notas con título default

!!! note "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

esto

## Code blocks

```
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

### Codeblocks con numeros de línea

``` python linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

=== "Tab 1"
```
COntenido tab 1
```

=== "tab2"
Contenido normalo no se

??? question "How can I add plugins to the Docker image?"

!!! warning "Automatically generated files"

Never make any changes in the `material` directory, as the contents of this
directory are automatically generated from the `src` directory and will be
overridden when the theme is built.
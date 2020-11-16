# Elementos para documentar

¡Qué bueno que se puedan usar emojis! :smile:

## Notas

### Nota con título default

!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### Nota con título personalizado

!!! note "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.

### Nota colapsable

??? note "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.

### Nota colapsable desplegada

???+ todo "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.

### Tipos de Nota

!!! note "Esta es: note"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! abstract "Esta es: abstract"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! info "Esta es: info"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! tip "Esta es: tip"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! success "Esta es: success"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! question "Esta es: question"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! warning "Esta es: warning"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! failure "Esta es: failure"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! danger "Esta es: danger"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! bug "Esta es: bug"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! example "Esta es: example"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! quote "Esta es: quote"
    Any number of other indented markdown elements.

    This is the second paragraph.



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

### Codeblocks con numeros de línea y resaltado

``` python linenums="1" hl_lines="2"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
### Codeblock en línea con resaltado

The `#!python range()` function is used to generate a sequence of numbers.

## Tab Content

=== "Tab 1"
    ``` php
    <?php
    $i = 12.4;
    echo "Never make any changes in the `material` directory, as the contents of this
    directory are automatically generated from the `src` directory and will be
    overridden when the theme is built."
    ```

=== "tab2"
    1. Never make any changes in the `material` directory, as the contents of this
    2. directory are automatically generated from the `src` directory and will be
    3. overridden when the theme is built.

## Notas al pié

Lorem ipsum[^1] dolor sit amet, consectetur[^2] adipiscing elit.

[^1]: directory are automatically generated from the `src` directory and will be
[^2]: Never make any changes in the `material` directory, as the contents of this
    directory are automatically genera

## Listas de tareas

* [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
* [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
* [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque

hola
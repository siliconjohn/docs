---
title: Integer
---
Integer
=======

Simple field for inputting whole numbers.

### Basic Configuration:

```yaml
        number:
            type: integer
```

### Example usage in templates:

```twig
{{ record.number }}
```

### Options:

The field has a few options to change the functionality of the field.

* `min` The minimum accepted value.
* `max` The maximum accepted value.
* `step` How much to "step" the value up and down when using the browser
  controls.

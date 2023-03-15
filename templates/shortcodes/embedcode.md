{% set data = load_data(path=path) -%}

```{{lan |safe}}
{{data| safe}}
```
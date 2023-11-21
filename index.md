# My `crocheting` hobby


![Image of a crochet doll]([https://images.app.goo.gl/8chSzNY3Cj9rkX3i7](https://images.app.goo.gl/4rL3VZJvvQD5N83p9)https://images.app.goo.gl/4rL3VZJvvQD5N83p9)

```
$python
def get_column_names(schemas, ds_name, sorting_key='column_position'):
    column_details = schemas[ds_name]
    columns = sorted(column_details, key=lambda col: col[sorting_key])
    return [col['column_name'] for col in columns]
```

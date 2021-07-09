Currently supports decoding strings, numbers and nulls.

Usage:
```python
import savefile
result = savefile.decode_sav("pai.sav")
print(result)
# {'name': 'Tech',
#  'role': 'General purpose',
#  'comments': None,
#  'version': 1.0,
#  ...
```
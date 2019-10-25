### weasyprint
---
https://github.com/Kozea/WeasyPrint

https://weasyprint.org/

```py
// weasyprint/tests/test_draw/test_transform.py

@assert_no_logs
def test_2d_transform_1():
  assert_pixels('image_rotate90', 8, 8, '''
  ''', '''
  ''')

@assert_no_logs
def test_2d_transform_2():
  assert_pixels('image_translateX_rotate90', 12, 12, '''
  ''')

```

```
```

```
```



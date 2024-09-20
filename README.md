```python
import sys
import platform

with open('system_info.txt', 'w', encoding='utf-8') as file:
  file.write(
      f"Sys version {sys.version}"
      )
```

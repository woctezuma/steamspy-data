# SteamSpy: Data

This folder contains data downloaded from SteamSpy on February 4, 2023.

### Data acquisition

```python
import json
import steamspypi

data = steamspypi.download_all_pages(num_pages=100)

with open('steamspy.json', 'w', encoding='utf8') as f:
    json.dump(data, f)

```

```
Downloading page=0 on Sat Feb  4 13:25:49 2023
Sleeping for 70 seconds on Sat Feb  4 13:25:50 2023
Downloading page=1 on Sat Feb  4 13:27:00 2023
Sleeping for 70 seconds on Sat Feb  4 13:27:00 2023
[...]
Downloading page=61 on Sat Feb  4 14:37:24 2023
Setting the number of pages from 100 (input) to 61 (actual).
```


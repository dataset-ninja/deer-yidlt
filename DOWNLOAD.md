Dataset **Deer (yidlt)** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/g/3/TV/ywHVJclMeHDOGZ3sHhxtboGgDrwBC1yeO400R70ewavnRy6LHsEa40vbHcLgnA5atl1sfNz3Wcw7rIpWKxCjwJQAjBbvJrMXIxjWkd29BfxBu9AZrl2ATqapecKV.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Deer (yidlt)', dst_path='~/dtools/datasets/Deer (yidlt).tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/deertracker/deer-yidlt/dataset/1/download)
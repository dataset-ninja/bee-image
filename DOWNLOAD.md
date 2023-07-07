Dataset **Bee Image Object Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/Z/3/vc/EEjRSq8W6Dr13BV1QfW1iIl2jMgFBbI56T5oPtQL8xGtsxQlngmSzwVzN96kgjRiTwc02VqP21glytWSuIXUg6179WmXYlwpAguMRvxsOcrbMWaaPqaT8pRicbuJ.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Bee Image Object Detection', dst_path='~/dtools/datasets/Bee Image Object Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/andrewlca/bee-image-object-detection/download?datasetVersionNumber=1)
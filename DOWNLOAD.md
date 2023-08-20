Dataset **Bee Image Object Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/8/1/0w/gDVfF0kMBuexmH6jOCyQryFDPgTp5Alh9z6zwFI1UZyMlmKNjlDc44BVIwx6FuuW7Z0g8dRDu5upbvUu7ORSVHpAREfUSU8QTQESPb640zY2mbQuUvpekoHm6vrU.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Bee Image Object Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/andrewlca/bee-image-object-detection/download?datasetVersionNumber=1).
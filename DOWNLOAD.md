Dataset **Bee Image Object Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/n/J/W4/58xrqoMZvoLBmhRfOPVw5V2FgR2mIr0VgcaqZItB7BS4mAlaKfmT1P4V5slnGAlkR91c0dvZgW7o1zEOk0dYXUnhFlHU6gDeqcGlxXlE3LIMoHxOKnuhujTdABoM.tar)

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
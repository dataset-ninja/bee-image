Dataset **Bee Image Object Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTMzM19CZWUgSW1hZ2UgT2JqZWN0IERldGVjdGlvbi9iZWUtaW1hZ2Utb2JqZWN0LWRldGVjdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICIyVHNaWmk4djd3UzE0UFBWSVNrVzFqc2hGQmw5emNGRy8rMVJjMXh2MmdJPSJ9?response-content-disposition=attachment%3B%20filename%3D%22bee-image-object-detection-DatasetNinja.tar%22)

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
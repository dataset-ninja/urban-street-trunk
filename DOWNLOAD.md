Dataset **Urban Street: Trunk** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/J/mT/ImbmPoWFwZblBD7DeCh1oh26JX3FTM1zSduw5ZRuyyDj41jtBTwF2pbALXXY3BYlaCaqdg0LNGSMH6ZnaFnKrWLNZ4HrV1aoBFWclyX7wDkUaWWdG1lHAs8aCv4x.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Urban Street: Trunk', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/erickendric/tree-dataset-of-urban-street-segmentation-trunk).
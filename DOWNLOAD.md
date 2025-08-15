Dataset **Urban Street: Trunk** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjU5Ml9VcmJhbiBTdHJlZXQ6IFRydW5rL3VyYmFuLXN0cmVldDotdHJ1bmstRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiZjNQcWZtU2Q5WCswTUNmVGExd2FZanFzUXRDQmtTMWxaL3BkeEF6RWEvcz0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22urban-street%3A-trunk-DatasetNinja.tar%22)

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
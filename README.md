# deep Classifier project

# workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config.
6. Update the components
7. Update the pipeline
8. Test run pipeline stage
9. run tox for testing your package
10. Update the dvc.yaml
11. run "dvc repro" for running all the stages in pipelineUpdate config.yaml

![img](https://raw.githubusercontent.com/snehalbalpande/FSDS_NOV_deepCNNClassifier/main/docs/image/Data%20Ingestion%402x%20(1)%20(1).png) 


MLFLOW_TRACKING_URI=https://dagshub.com/snehalbalpande1/FSDS_NOV_deepCNNClassifier.mlflow \
MLFLOW_TRACKING_USERNAME=snehalbalpande1 \
MLFLOW_TRACKING_PASSWORD=133ca0c75ba1b70a6104e333959b14b41c4d0e17 \
python script.py
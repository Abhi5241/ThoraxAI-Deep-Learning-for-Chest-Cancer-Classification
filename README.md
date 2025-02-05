# ThoraxAI-Deep-Learning-for-Chest-Cancer-Classification

 - [Data link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view?usp=sharing)

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

### Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/Abhi5241/ThoraxAI-Deep-Learning-for-Chest-Cancer-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=abhi5241 \
MLFLOW_TRACKING_PASSWORD=2a7802942d8464177271b2a487be8b7dbfd6cf65 \
python script.py
```



### RUN from bash terminal

```bash
export https://dagshub.com/Abhi5241/ThoraxAI-Deep-Learning-for-Chest-Cancer-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=abhi5241
export MLFLOW_TRACKING_PASSWORD=2a7802942d8464177271b2a487be8b7dbfd6cf65

```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag
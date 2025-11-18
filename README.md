MACHINE LEARNING WORKFLOW STEPS in Azure python SDK 

1.Connect to workspace

2.Register data

3.Create env

4.Create compute

5.Submit job

6.Register model

7.Deploy model

azureml-ml-template/
├─ README.md
├─ config.py
├─ env.yml
├─ data/
│   └─ train.csv              # your training data (example)
├─ src/
│   └─ train.py               # your training script
└─ azureml/
    ├─ connect.py             # workspace connection
    ├─ data_asset.py          # register data asset
    ├─ environment.py         # create environment
    ├─ compute.py             # create/attach compute cluster
    ├─ submit_train.py        # submit training job
    ├─ register_model.py      # register trained model
    └─ deploy_online.py       # deploy model as online endpoint


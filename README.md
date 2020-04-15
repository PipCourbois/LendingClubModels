## LendingClubModels

Learn to run Deep Models for predicting who will pay back loans using the LendingClub data:

#### Tools to learn
1.  Keras
1.  Docker

#### Methodology to learn
1.  [Deep and wide models](https://ai.googleblog.com/2016/06/wide-deep-learning-better-together-with.html)
1.  [Visualizing embeddings](https://towardsdatascience.com/neural-network-embeddings-explained-4d028e6f0526)
1.  non-symetric loss
1.  [Model interpretation](https://gilberttanner.com/blog/introduction-to-machine-learning-model-interpretation) - feature importance, partial dependencies, [Lime](https://github.com/marcotcr/lime), and [Shap](https://towardsdatascience.com/explain-your-model-with-the-shap-values-bc36aac4de3d)

#### Steps and statuses
- [x] Download [LendingClub data](https://www.kaggle.com/wendykan/lending-club-loan-data) -- Q4 data completed
  - [x] [data dictionary](https://docs.google.com/spreadsheets/d/16fqmVyjloON5Efo51wHtyNodsNwEPvSzkYsUP0QoZm4/edit#gid=1283882092)
  - [x] [data sample](https://docs.google.com/spreadsheets/d/13wa-cJcNWSenJAEBTVo9u0DpoiBe7ruVIAiPA2sDnyE/edit#gid=421910670)
- [x] Jupyter Notebook on Mac
  - Because Groupon used brew, I have [this](https://stackoverflow.com/questions/45495753/jupyter-not-found-after-pip-install-jupyter) problem.  
  - Command to start notebook is: python -m notebook
- [ ] Docker image within git repository 
  - [x] Docker tutorial -- [Jupyter Docker Stacks user guide](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html) is fantastic.  
  - [x] Python data-science basic image -- start with [jupyter/tensorflow-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#core-stacks)
  - [x] Run the jupyter/tensorflow-notebook
    ```
    docker run -p 8888:8888 jupyter/tensorflow-notebook:latest
    ```
  - [x] How to save a notebook into this github?  use the -v command; search for -v [here](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/common.html)
    ```
    docker run -p 8888:8888 -v /Users/pcourbois/LendingClubModels:/home/jovyan/work jupyter/tensorflow-notebook:latest
    ```
  - [x] import data, add data to github
- [x] EDA -- not started
- [ ] Start blog post and notes -- not started
- [ ] Identify target variable -- keep it simple -- not started
- [ ] Feature engineering -- not started

# OCI Object detection

The idea with this repository is to create a custom dataset, using the datalabeling and vision service of Oracle Cloud, to detect plastic botels in rivers 

I wrote a blog explaining how the service of data labeling and vision service works https://medium.com/@carlgira/ai-vision-model-on-oci-for-object-detection-c47ac63114fc


I'll be using the plastic river dataset https://huggingface.co/datasets/Kili/plastic_in_river

<img src="img/dataset-cover.png"/>

## Initial Setup

1. Follow the instructions to configure oci cli and to create API keys to authenticate against OCI that are in this blog https://medium.com/@carlgira/install-oci-cli-and-configure-a-default-profile-802cc61abd4f

2. Create the enviroment using poetry

```
    poetry install
    poetry shell
```

3. Once the enviroment is activated start jupyter.

```
    jupyter-lab
```


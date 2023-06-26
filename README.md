# NanoFoldLM
<p align="center"><img src="https://github.com/YaadLuria/NanoFoldLM/blob/main/images/logo1.jpeg" height="250"/></p>

HUJI's 3D Data Processing in Structural Biology Hackathon (group 3, project 2 "The language model folder")


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YaadLuria/NanoFoldLM/blob/main/TheLanguageModelFolder.ipynb)



How to run NanoFoldLM from google Colaboratory:

    1. Open the Colab notebook NanoFoldLM.ipynb, and connect to GPU for faster run
    2. Add protein sequence and choose embedding size
    3. You can also compare to a solved pdb structure


### Pre-trained Models you can use: <a name="available-models you can use"></a>

| `esm.pretrained.`           | #layers | #params | Dataset | Embedding Dim |  Model URL (automatically downloaded to `~/.cache/torch/hub/checkpoints`) |
|---------------------|---------|-------------|---------|---------------|-----------------------------------------------------------------------|
| `esm2_t33_650M_UR50D`        | 33           | 650M        | UR50/D 2021_04                           | 1280 |  https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t33_650M_UR50D.pt         |
| `esm2_t30_150M_UR50D`        | 30           | 150M        | UR50/D 2021_04                           | 640  |  https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t30_150M_UR50D.pt         |
| `esm2_t12_35M_UR50D`         | 12           | 35M         | UR50/D 2021_04                           | 480  |  https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t12_35M_UR50D.pt          |
| `esm2_t6_8M_UR50D`           | 6            | 8M          | UR50/D 2021_04                           | 320  |  https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t6_8M_UR50D.pt            |

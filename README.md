# XAI a partir de caminhos definidos por cluster
Projeto criado para o trabalho da disciplina de aprendizagem profunda. O objetivo é descobrir caminhos de decisão a partir da clusterização dos vetores de unidade de ativação de cada camada. Baseado no artigo presente em https://doi.org/10.48550/arXiv.2210.00319.

## Configuração do ambiente

```bash
conda create -n "nn_pathfinder" python=3.12 ipython -y
conda activate nn_pathfinder
pip install -r requirements.txt
```
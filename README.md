# FixMatch

Este repositório contém o trabalho sobre FixMatch e seus experimentos para a disciplina de Aprendizado profundo na graduaçaõ de Ciência de Dados e Inteligência Artificial na FGV-EMAp.

## Arquivos:
* **DeepLearnig FixMatch.pdf**: slides usados no vídeo de apresentação;
* **FixMatch_no_cutout.ipynb**: exeperimentos do fixMatch variando a quantidade de labels por classe sem transformação de cutout, com 50 e 200 épocas, além de utilizar os modelos base do ResNEt-18 e Wide ResNet-50-2;
* fix_exp_lambda_u_thresh.ipynb: experimentos variando o $\lambda_u$ e $\tau$ durante o treinamento, aqui aplicamos cutout;
* **Experiments\exp1234WithCutout_TriPath.ipynb**: experimentos de tripath augmentation
* **Experiments\exp1234WithCutout50Epochs.ipynb**: experimetos variando a quantidade de labels com o modelo ResNet com 50 épocas e aplicando o cutout

[Vídeo de apresentação](https://youtu.be/m6EFN5rFBq8)

Integrantes:
* Henrique Borges
* Paula Eduarda de Lima
* Mariana Fernandes Rocha

# TRANSFER-LEARNING-YOLO5

Projeto de Transfer Learning com YOLOv5 utilizando o dataset COCO 2017 para aprimorar a detecção de objetos.

# Descrição

Este repositório contém o código para realizar transfer learning usando o modelo YOLOv5s pré-treinado no COCO 2017. O objetivo é aprimorar o desempenho do modelo em detecção de objetos, mantendo as 80 classes originais do COCO.

# O projeto inclui:

Preparação do dataset COCO.

Conversão das annotations para formato YOLO.

Criação de arquivo YAML para treinar com YOLOv5.

Código para treinamento e inferência com transfer learning.

Desativação do W&B para evitar prompts interativos.

Observação: Este projeto foi usado como desafio de finalização de curso de Machine Learning.

# Requisitos

Python 3.8 ou superior

PyTorch 2.x

CUDA (opcional, para treino com GPU)

# Bibliotecas adicionais:
pip install -r requirements.txt

# Referências

YOLOv5 GitHub

COCO Dataset

Documentação YOLOv5

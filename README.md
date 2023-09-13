# Aprendizagem-Profunda
## Sistema de Deteção e Classificação de Máscaras Faciais

Devido ao facto de o Github não suportar ficheiros com mais de 25Mb, o ficheiro *.zip* com a totalidade dos ficheiros e imagens pode ser descarregado [aqui](https://drive.google.com/file/d/1EYgltvulkoBQu4rZFpy2tuhpqJqMYT47/view)

Devido ao seu tamanho, o modelo final poderá ser tranferido na [DropBox](https://www.dropbox.com/s/9f0d83rmuxnnrw3/CNNModel-final25.pth?dl=0) ou, caso não seja possível, no [WeTransfer](https://we.tl/t-h1LvZAP1SI) (indisponível ao fim de 7 dias)


O presente projeto conta com os seguintes componentes:

- **[face-mask-detection-pytorch.ipynb](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/blob/main/face-mask-detection-pytorch.ipynb):** Ficheiro com todo o processo relativo ao modelo desenvolvido, desde obtenção de dados, tratamento, visualização, análise e definição do modelo.
- **[testSetMaker](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/tree/main/testSetMaker):** Funcionalidades relativas ao conjunto de dados utilizados para teste 
  - **[testModel.ipynb](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/blob/main/testSetMaker/testModel.ipynb):** Ficheiro correspondente ao modelo obtido através do Kaggle para comparação com o modelo desenvolvido
  - **[makingDataset.ipynb](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/blob/main/testSetMaker/makingDataset.ipynb):** Ficheiro para produzir um conjunto de imagens utilizadas para teste e o *.csv* correspondente (com as *bounding boxes* e *labels*)
- **[maskIncorrectDataMaker](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/tree/main/maskIncorrectDataMaker):** Ficheiro para produzir um conjunto de imagens com a máscara colocada incorretamente
- **[faceDataMaker](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/tree/main/faceDataMaker):** Funcionalidades para obter um conjunto de imagens sem máscara


----
### Fontes:

- **[YOLOFace](https://github.com/elyha7/yoloface)**: Modelo pré-treinado do YOLO para deteção de caras (*face detection*)
- **[Face Mask Detection Dataset](https://www.kaggle.com/datasets/wobotintelligence/face-mask-detection-dataset)**: Conjunto inicial de imagens de faces
- **[Human Faces](https://www.kaggle.com/datasets/ashwingupta3012/human-faces?select=Humans)**: Conjunto de imagens de faces sem máscara
- **[Face Mask Detection](https://www.kaggle.com/datasets/vijaykumar1799/face-mask-detection)**: Conjunto de imagens de faces complementar

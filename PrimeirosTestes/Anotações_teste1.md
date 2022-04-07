# Diario de Bordo sobre o Teste1

## Bibliotecas Utilizadas:
  * math = Calculos de área e circunferencia
  * numpy = Manipulação de matrizes
  * scipy = Fornece ferramentas adicionais para computação de arrays e fornece estruturas de dados especializadas, como matrizes esparsas e árvores k-dimensional.
  * Pandas = Manipulação de dados
  * seaborn = visualização de dados Python baseada em matplotlib.
  * Sklearn = Algoritmos de aprendizagem para classificação e regressão
  * OpenCV = Manipulação da Imagem
  
## Métodos do OpenCV utilizados:
  * imread = Ler uma imagem colorida do sistema de arquivos
     * Esta função recebe como entrada o caminho para o arquivo e retorna a imagem como uma matriz dimensão NumPy N. 
     * A imagem é lida no formato BGR.
     * Link = https://www.geeksforgeeks.org/python-opencv-cv2-imread-method/
  * Split = Decompor uma imagem em seus três canais de cor
     * Cada canal é representado como uma matriz dimensão NumPy com duas dimensões;
     * Ao exibir os resultados teremos 3 imagens em escala de cinza.
     * Link = https://techtutorialsx.com/2020/03/02/python-opencv-splitting-image-channels/
     
## Etapas Manuais:
  * Separação da imagem nos 3 canais - RGB
  * Redimensionamento da Imagem
  * Binarização e Limiarização
  * Definição do contorno dos objetos
  * Identificação dos contos
  * Captura das Features (Dataframe)

## Etapas (Kmeans + OpenCV):
  * Definição dos agrupamentos

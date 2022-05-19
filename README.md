# PalmaS: Sistema Computacional de Apoio à Decisão sobre o Manejo Integrado de Cochonilhas do Carmin e de Escama na Cultura da Palma Forrageira

## Introdução: 
    * A palma (Opuntia e Nopalea) é uma das principais fontes de suporte alimentar de bovinos, caprinos, ovinos e tem proporcionado, nos últimos anos, uma verdadeira mudança no sistema de criação de ruminantes no Rio Grande do Norte. no semiárido. A infestação por cochonila de escama nas raquetes de palma consiste num problema grave e que necessita de estratégias de controle. A observação de uma superfície pulverulenta (grande quantidade de pontos esbranquiçados), ou seja, com aparência de pó fino nas raquetes, pode indicar a reinfestação da palma por ninfas de 1° e/ou 2° ínstares (estágios de desenvolvimento na fase imatura), sinalizando a presença de novas gerações e consequente aumento populacional da praga. Ao se detectar essa situação, sugere-se aos produtores que medidas de controle sejam adotadas. Entre estas medidas, destacam-se os métodos naturais (óleos) e biológicos (insetos). 
    * No estudo em laboratório do efeito de determinados tratamentos, a eficácia do tratamento é feita pela seleção de área de observação na raquete e, com microscópio, as cochonilas são contadas a olho nu. Esta verificação pode ser otimizada direcionando o esforço e perícia do técnico para as análises em si, e não à contagem, que pode ser otimizada por meio de processamento digital de imagens adquiridas por câmeras e identificação por meio de técnicas de classificação de aprendizagem de máquina.
    
## Objetivos do Projeto:
    a) construção de dataset de imagens significativas de diferentes níveis de infestação da cochonila de escama, em diferentes instares; 
    b) estudo de algoritmos de detecção e classificação por aprendizagem de máquina, inclusive por diferenciação de instares; 
    c) desenvolvimento de software para automação do processo;

## Metodologia:
    * O trabalho consiste na produção de datasets de imagens com configuração definida, zoom, resolução, iluminação, em laboratório. 
    * Segue-se o treinamento de modelos de classificação, com o estudo de viabilidade de técnicas clássicas, como haar cascade, e técnicas atuais de aprendizagem de máquina

## Bibliotecas e Ferramentas utilizadas:
    * Principal:   
         + Linguagem: Python
         + IDE: Google Colaboratory
         + Biblioteca OpenCV - cv2 = https://docs.opencv.org/4.2.0/d6/d00/tutorial_py_root.html   
            - Moments = https://docs.opencv.org/3.4/dd/d49/tutorial_py_contour_features.html
    
    *   math = https://docs.python.org/3/library/math.html
    *   numpy = https://numpy.org/doc/stable/user/whatisnumpy.html
    *   scipy - stats = https://scipy.github.io/devdocs/tutorial/general.html    
    *   pandas = https://pandas.pydata.org/docs/getting_started/overview.htmlf
    *   seaborn = https://seaborn.pydata.org/introduction.html
    *   Sklearn.cluster - Kmeans = https://scikit-learn.org/stable/getting_started.html
    *   data_augumentation = https://www.tensorflow.org/tutorials/images/data_augmentation

## Inspirações:
    * https://github.com/Gus-1003/Processamento-Digital-de-Imagem
    
    * https://github.com/alysonmiguel/PalmaS
    
    * https://github.com/josenalde/palmaS_counting_system

##  Livro:
    *  Processamento Digital de Imagens 3-Edição : https://drive.google.com/file/d/19yJncgIo2LsuKdRp224rObSpgvr9DubS/view?usp=sharing
   
   
## Conversor de RGB:
    * https://toolstud.io/color/rgb.php

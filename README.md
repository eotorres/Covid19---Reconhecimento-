

<h2 align="center">Detector de Mascara Covid-19 </h2>
<h3>Sistema de detecção facial que reconhece o uso ou não de mascaras!</h3>
<p>Este script foi desenvolvido para detecção através de reconhecimento facial, machine learning e deep learning.</p>

# Requisitos:
- Python 3.7 
- Tensorflow
- Keras
- Numpy
- Sklearn (scikit-learn)
- Imutils 
- Pillow
- h5py
- Matplotlib


# Dataset de imagens:
<p>Você deve criar uma pasta e adicionar o nome de dataset , dentro dela extriar os zips com_mascara e sem_mascara. Caso queira, pode adicionar mais imagem assim o modelo passará a ter mais recurso de treino assim o desempenho do machine learnig e a execução mais precisa de nosso face recognition com atributo de máscaras.</p>

# Executando o trainer:
<p>Após ter todas as bibliotecas instaladas basta rodar o arquivo script_treinando_modelo.py, ele irá treinar as imagens da sua pasta dataset, quando mais  (imagens incluidas) no dataset e varios processamentos de treino melhor será o retorno.</p>

# Executando o detector de imagens:
<p>Após concluido o treino e salvo o arquivo -mask_detector.model-  na pasta /detectores você já pode iniciar suas análises de imagem.</p>

# Executando o detector com sistema de camera:
<p>Após concluido o treino e salvo o arquivo -mask_detector.model-  na pasta /detectores você já pode iniciar suas análises de imagem da camera ou de videos, basta abrir o arquivo - script_detectar_mascaras_com_camera_webcam.py - e ele ira detectar automaticamente.</p>

   
 # Tempo de execução:
 <p>O tempo de execução de todo processo e qualidade varia de maquina para maquina, então avaliar qual melhor se enquadra com seus recursos e executar, caso preferir, tente executar pelo colab.</p>
 


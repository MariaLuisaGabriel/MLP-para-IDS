# Aplicação de Multilayer Perceptrons em Sistemas de Detecção de Intrusão
Repositório do primeiro trabalho da matéria Inteligência Computacional - UFU/FACOM

Feito por:
- Maria Luísa Gabriel Domingues [maria.luisa.gabriel.domingues@gmail.com](maria.luisa.gabriel.domingues@gmail.com)
- Giovanna Oliveira Martins [gimartins15@outlook.com](gimartins15@outlook.com)
- João Pedro Ferreira Pereira 

A partir de uma busca sistemática por artigos que aplicam MLP na prática, encontramos o artigo [A multilayer perceptron artificial neural network approach for improving the accuracy of intrusion detection systems.](https://pdfs.semanticscholar.org/82b1/6b360d4bfc11c1da3d44ca797ac01be65024.pdf), e baseando-se em sua aplicação, desenvolvemos um modelo semelhante, com o objetivo de conquistar uma taxa de acertos maior para a mesma [base de dados(kdd-train)](https://www.kaggle.com/datasets/kiranmahesh/nslkdd/data) usada no artigo.

Para medir a taxa de acertos, usamos três métricas: matriz de confusão, acurácia e F1-Score.

Para tentar melhorar a taxa do MLP2 feito no artigo, implementamos um MLP2 nosso com a base do sklearn da linguagem Python, e começamos a brincar com as especificações da rede, variando a taxa de aprendizado, a função de ativação, o número de neurônios por camada e por fim o número de camadas escondidas.

Finalmente, conseguimos gerar um MLP com maior taxa de acertos (de forma bem distribuída) que o MLP2 do artigo, com um multilayer perceptron de 3 camadas, com 32, 16 e 16 neurônios nas camadas escondidas, respectivamente, com taxa de aprendizado 0.01 e função logística de ativação.

![image](https://github.com/user-attachments/assets/00c2ab9e-1042-476b-bfa0-902da8e61cfd)

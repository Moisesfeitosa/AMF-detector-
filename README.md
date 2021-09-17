# AMF-detector-

Apresentamos nesse código uma tentativa de segmentar hifas de fungo micorrízico arbuscular (FMA) contidos em imagens de raízes obtidas através de microscopia. Para tal utilizamos uma UNet com algumas modificações como visto no código acima. 
Posteriormente ao treinamento da rede, apresentamos uma proposta de teste da capacidade de predição do modelo. Nesse passo, o usuário deve carregar o modelo salvo em formato h5. Nessa tarefa de testagem, imagens inéditas, ou seja, que a rede não viu no processo de validação e treinamento, devem ser apresentadas e o modelo deve testar sua capacidade de predição das hifas contidas ali na imagem. 
Implementamos o treinamento e testagem do modelo utilizando um jupyter notebook no google colab. Para a implementação do modelo, utilizamos uma GPU fornecida pela plataforma. Para a testagem do modelo, o uso da GPU não se faz necessária. 

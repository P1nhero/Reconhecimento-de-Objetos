# Rastreamento de Objetos

## Descrição do projeto  
Este projeto realiza o rastreamento de objetos selecionados e identifica-os com base em sua forma, utilizando técnicas de visão computacional e aprendizado de máquina.

## Instruções de instalação  
1. Instale o [Visual Studio Code (VS Code)](https://code.visualstudio.com/).  
2. Instale o [Anaconda Navigator](https://www.anaconda.com/products/distribution).  
3. (Opcional) Instale o [Iriun Webcam](https://iriun.com/) no computador e no celular, caso seu computador não possua webcam.  
4. Utilize o [Teachable Machine](https://teachablemachine.withgoogle.com/) para criar o modelo de rastreamento dos objetos desejados.  
5. Treine o modelo com as classes de objetos que deseja reconhecer.  
6. Exporte o modelo no formato Keras (.h5) para TensorFlow.  
7. Baixe o arquivo `classificacao_5_objetos-v4.py`, que contém o código principal do projeto.  
8. Baixe o arquivo `env_teste_PI_2024.yml`, que é o ambiente virtual com todas as dependências configuradas para o Anaconda Navigator.

## Instruções de uso  
1. Crie uma nova pasta no seu computador para armazenar todos os arquivos do projeto.  
2. Extraia o arquivo do modelo Keras (.h5) dentro dessa pasta.  
3. Copie o arquivo `classificacao_5_objetos-v4.py` para essa mesma pasta.  
4. Abra o Anaconda Navigator.  
5. Na aba *Environments*, importe o ambiente virtual a partir do arquivo `env_teste_PI_2024.yml`.  
6. Com o ambiente virtual ativado, abra o VS Code pelo próprio Anaconda Navigator.  
7. No VS Code, abra a pasta onde os arquivos estão armazenados.  
8. Abra o arquivo `classificacao_5_objetos-v4.py`.  
9. Verifique se o ambiente virtual `env_teste_PI_2024` está selecionado no VS Code.  
10. Execute o projeto.

**Observação:** Caso ocorra algum erro relacionado ao arquivo do modelo, verifique se o nome do arquivo `keras.model.h5` está com underline (_) ao invés de ponto (.). Caso esteja incorreto, altere o nome do arquivo, não o código.

## Créditos  
Projeto realizado no Laboratório de Sistemas de Informação da UFOPA.

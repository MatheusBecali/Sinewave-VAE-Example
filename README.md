# Projeto de Treinamento de VAE em Dados de Onda Senoidal

Este projeto implementa e treina uma Variational Autoencoder (VAE) usando dados de onda senoidal gerados artificialmente. O objetivo é avaliar a capacidade do VAE de reconstruir os dados de entrada e visualizar a diferença entre os dados originais e reconstruídos.

## Arquivos

- `Seno-VAE.ipynb`: Script principal que contém a implementação do VAE, a preparação dos dados, e o loop de treinamento.

## Requisitos

- Python 3.x
- Bibliotecas listadas em `requirements.txt`:
  - numpy
  - pandas
  - torch
  - matplotlib
  - sklearn

## Como usar

1. **Instalar dependências**:
   ```
   pip install -r requirements.txt
   ```

2. **Executar o script de treinamento**:
   
    Basta executar o `Run all` do seu Jupyter Notebook.

4. **Visualizar resultados**:

    Após o treinamento, os resultados da reconstrução dos dados podem ser visualizados através dos gráficos gerados pelo script.


## Contribuições
Sinta-se à vontade para fazer fork deste projeto, abrir issues e enviar pull requests. Suas contribuições são bem-vindas!

## Licença
Este projeto é licenciado sob os termos da licença MIT.

## Próximos Passos (TODO)

1. Converter o arquivo `.ipynb` para `.py`, separando o codigo em 3 arquivos:
   - `train_vae.py`: Script principal que contém a implementação do VAE, a preparação dos dados, e o loop de treinamento.
   - `create_dataset.py`: Contém a função para gerar o conjunto de dados de onda senoidal.
   - `models.py`: Contém a definição da arquitetura do VAE e dos blocos ResNet1D utilizados.

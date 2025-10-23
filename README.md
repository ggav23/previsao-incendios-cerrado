# Previsão de Risco de Ignição de Incêndios no Cerrado com Deep Learning

Descrição
Este repositório contém o código e a documentação do projeto de artigo acadêmico para a disciplina de Projeto Aplicad-Metodologia Ciêntifíca no curso de Ciência da Computação. O objetivo é desenvolver um modelo de Deep Learning,utilizando uma arquitetura espaço-temporal (ConvLSTM), para prever o risco de ignição de incêndios no bioma Cerrado brasileiro.

Equipe
[Guilherme Vieira]

[Igor Marques]

[Lucas Santana]

[Kaua Veit]

[Elvis Teixeira]

Estrutura do Repositório
/data: Armazena os datasets. (Obs: Dados brutos não são versionados).

/notebooks: Contém os notebooks Jupyter/Colab para análise exploratória, pré-processamento e experimentação de modelos.

/src: Código-fonte Python com funções e classes reutilizáveis.

/docs: Documentação do projeto, incluindo o documento de escopo e o artigo final.

/results: Resultados gerados, como mapas de risco, gráficos e métricas de avaliação.

Como Executar o Projeto
**Clone o repositório: git clone https://github.com/Apelaun/previsao-incendios-cerrado  

Configure o ambiente: O ambiente principal de desenvolvimento é o Google Colab. As dependências estão listadas no arquivo requirements.txt.

Execute os notebooks: Abra os notebooks localizados na pasta /notebooks no Google Colab para reproduzir os experimentos.

Fontes de Dados
MapBiomas Fogo: Cicatrizes de incêndios.

ERA5-Land: Dados meteorológicos.

MODIS/Landsat: Índices de vegetação e temperatura da superfície.

SRTM: Dados topográficos.

E outras fontes detalhadas na documentação.

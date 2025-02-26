# <p align= "center"> **Estágio de férias - Explicable AI & Supercondutividade** 💻⚛️ </p>

## Aplicação de técnicas de explicabilidade de modelos de Machine Learning (ML) em um dataset referente a temperatura crítica de materiais supercondutores
![Status](https://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge)

### Introdução 🧪
<p align="justify">
  A supercondutividade pode ser definida como um fenômeno físico caracterizado pela expulsão dos campos magnéticos de um material, bem como a resistência nula do mesmo a passagem de corrente elétrica [1]. Apesar do fenômeno ter sido descoberto em 1911, ainda não se sabe quais são as propriedades que podem levar um material a vir se tornar um supercondutor. Dessa forma, dada a vasta aplicabilidade desses materiais, torna-se fundamental o estudo de suas principais propriedades. 
</p>

<p align="justify">
  Nesse viés, tem-se que a temperatura crítica - isto é, a temperatura mínima a qual o material precisa ser submetido para atuar como um supercondutor - aparece como um dos principais atributos que podem auxiliar na compreensão e, até mesmo, aplicação desses materiais. 
</p>
  
  <p align="justify">
  Um dos principais datasets referentes a supercondutores busca, justamente, utilizar características obtidas a partir de propriedades desses materiais, para a previsão da temperatura crítica. Presente na base de dados UCI Machine Learning, o dataset descrito no artigo "Data driven Statistical model for predicting the critical temperature of a superconductor" [2] busca criar features a partir de características deduzidas a partir da fórmula química desses materiais (i.e massa atômica, primeira energia de ionização, raio atômico, densidade, afinidade eletrônica, temperatura de fusão, condutividade térmica e valência). Aplicando medidas estatísticas( como média simples, ponderada, geométrica e geométrica ponderada, entropia simples e ponderada, range simples e ponderado e desvio padrão simples e ponderado), foi possível então criar 81 features que se relacionam com a temperatura crítica.
  </p>
  
  <p align="justify">
  Com o objetivo de investigar como essas propriedades podem se relacionar com a definição de um supercondutor, portanto, esse trabalho busca treinar modelos de aprendizado de máquina e, concomitantemente, aplicar variadas técnicas de <em>Explicable AI</em> (do português, inteligência artificial explicável), no dataset descrito. Ao final da investigação, visa-se uma melhor compreensão da influência das features na previsão do target determninado.
</p>

### Pré-requisitos 📄
<p align= "justify">
Para utilizar os notebooks presentes nesse repositório, é necessário ter conhecimentos prévios de Python, estatística e ciência de dados, bem como utilizar um editor de códigos dessa linguagem. Em editores, como o Visual Studio Code (VS Code), é possível clonar o repositório para maior praticidade na obtenção dos arquivos. Nos demais casos, os arquivos podem ser baixados diretamente do repositório.
</p>

Para rodar os arquivos, além da utilização da versão mais atual da linguagem Python (3.13), é preciso realizar a instalação das bibliotecas listadas abaixo:
```bash
pip install pandas
pip install seaborn
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install statsmodel
```
### Notebooks 📓
<ul>
  <li> <em> Linear Regression </em>: Contém testes com diferentes regressões lineares (OLS, Ridge, Lasso e GLM), bem como a análise de Feature Importance desses modelos. </li>
  <li><em>Shap and Lime</em>: Um notebook específico para a análise de Feature Importance com as bibliotecas SHAP e LIME. </li>
  <li> <em>Feature Selection </em>: Contém testes com diferentes técnicas de redução de dimensionalidade. </li>
</ul>

### Referências Gerais 📚
[1] Superconductivity - an overview | ScienceDirect Topics. https://www.sciencedirect.com/topics/materials-science/superconductivity. Acesso em 25 de fevereiro de 2025.

[2] Hamidieh, Kam. “A Data-Driven Statistical Model for Predicting the Critical Temperature of a Superconductor”. Computational Materials Science, vol. 154, novembro de 2018, p. 346–54. Semantic Scholar, https://doi.org/10.1016/j.commatsci.2018.07.052.

* As demais referências estão contidas nos respectivos notebooks


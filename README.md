<div align="center">
<h1> Modelagem e Previsão da Incidência de Dengue no Espírito Santo: Uma Comparação de Técnicas de Aprendizado de Máquina</h1>

<!-- <--!span><font size="5", > Efficient and Robust 2D-to-BEV Representation Learning via Geometry-guided Kernel Transformer
</font></span> -->

Alefe Gadioli - alefe.gadioli@edu.ufes.br

Priscilla Benevides - priscilla.benevides@edu.ufes.br
<!-- <a href="https://scholar.google.com/citations?user=pCY-bikAAAAJ&hl=zh-CN">Jinwei Yuan</a> -->
<div><a href="https://github.com/intel-comp-saude-ufes/2024-1-P1-Dengue-prediction/blob/main/1%C2%AA_Projeto_Intelige%CC%82ncia_Computacional_em_Sau%CC%81de.pdf"> Artigo </a> </div> 

<div><a href="https://youtu.be/u0VNPSf90hY"> Video de Apresentação </a> </div> 

</div>

## Descrição do Projeto

Este projeto investiga a modelagem e previsão da incidência de dengue no estado do Espírito Santo utilizando técnicas de aprendizado de máquina. Foram avaliadas quatro técnicas principais: Regressão Linear, Random Forest, Gradient Boosting e MLP Regressor. Os dados foram coletados de diversas fontes, abrangendo um período de 17 anos, e incluem informações meteorológicas e de incidência de dengue.

A dengue é uma doença viral transmitida pelo mosquito *Aedes aegypti*, e sua incidência tem aumentado significativamente nas últimas décadas. Modelos precisos de previsão podem auxiliar na tomada de decisões e no planejamento de intervenções de saúde pública para mitigar os surtos de dengue.

## Resultados

Os resultados indicam que o modelo Gradient Boosting apresentou o melhor desempenho, com um Erro Quadrático Médio (MSE) de 678.645,56 e um Coeficiente de Determinação (R²) de 0,76. O Random Forest também mostrou bons resultados, com MSE de 879.097,91 e R² de 0,69. A Regressão Linear e o MLP Regressor tiveram desempenhos inferiores, com MSEs de 1.909.247,10 e 957.541,69, respectivamente.

Este estudo demonstra que técnicas avançadas de aprendizado de máquina podem fornecer previsões precisas e robustas da incidência de dengue, auxiliando na tomada de decisões e no planejamento de intervenções de saúde pública.

## Requisitos

- **Python 3.x**
- **Bibliotecas:** pandas, numpy, scikit-learn, matplotlib

## Como Executar

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/alefeg2020/2024-1-P1-Dengue-prediction.git
    cd 2024-1-P1-Dengue-prediction
    ```

2. **Instale as dependências necessárias:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```

3. **Abra o Notebook:**
    ```bash
    Abra o notebook: Notebook_Dengue.ipynb
    ```
  
4. **Substitua o caminho do dataset:**
    ```bash
    file-path: "caminho do arquivo"
    ```
5. **Execute**

# Descritor HoG

Este projeto é uma implementação do descritor HoG, demonstrando como resultado cinco histogramas gerados a partir de cinco imagens que passaram pelo algoritmo.

## Instalação

Para executar o projeto, certifique-se de ter um ambiente python para executar o código. Além disso, baixe as bibliotecas utilizadas pelo script.

```bash
pip install cv2
pip install matplotlib
pip install numpy
```
Você também pode executar o projeto no ambiente do Google Colab, para isso disponibilizei o link abaixo. Basta entrar e em Runtime clicar em RunAll. Não esqueça de fazer upload de uma imagem do dataset e setar seu nome na primeira célula.

<a href="https://colab.research.google.com/drive/1uKubWEx8Q5LGFYW__LYLBh5TR-nkkr6-?usp=sharing" target="_blank">Google Colab Notebook</a>

## Dataset

As imagens utilizadas neste projeto estão na pasta "Imagens" deste repositório. Certifique-se de apontar o caminho correto no código.

```bash
imagem = cv2.imread('imagem_5.jpg')
```

## Histogramas

Os resultados gerados pelo o algoritmo são histogramas. Para as imagens utilizadas no projeto, cada histograma esta na pasta "Histogramas" deste projeto.

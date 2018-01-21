# Introdução

Este repositório contém exercícios e experimentos exibidos no curso de Machine Learning de Stanford disponível pelo [Coursera](https://www.coursera.org/learn/machine-learning/).

O repositório possui três principais pastas:

* `notebook`: contendo arquivos com extensão `.ipynb`
* `source`: contendo os scripts a serem executados pelo programa Octave
* `results`: contendo resultados gráficos, que não deve ser rastreados pelo git

# Rodando localmente

Você precisa instalar o programa `Octave` na sua máquina para rodar scripts aqui armazenados.

Para utilizar o `Octave` nos Jupyter Notebooks, é necessário recompilar o Kernel. Você pode seguir as instruções providas [neste link](https://github.com/Calysto/octave_kernel).

Você também pode executar o `Octave` utilizando uma imagem Docker, da seguinte maneira:

```
~ (master) $ docker run --rm -it -v $(pwd):/source schickling/octave
```
<div id="topo"></div>

📜 Índice
===

* [Sobre o projeto](#about)
* [Pré-requisitos](#install)
* [Configuração](#setup)

## 💻 Sobre o projeto <a name="about"></a>
O projeto consiste em aplicar os métodos de fatoração de matrizes Mínimos Quadrados Alternados e SVD em dados de votações da Organização das Nações Unidas (ONU), com o intuito de visualizar a proximidade dos países, podendo agrupá-los caso haja alguma divisão notória.

Desse modo, o principal tema desse trabalho é a redução de dimensionalidade que se trata da transformação de dados que se encontram num espaço dimensional alto para dados em dimensões mais baixas. Essas transformações são feitas, pois as representações em dimensões menores podem conter diversas propriedades e revelar informações significativas do dado original, que podem ser investigadas em processos de clusterização e visualização de dados que são viáveis devido à essa manipulação.
 
Para mais detalhes teóricos acesse o relatório [clicando aqui](https://github.com/danielShz/Trabalho-Final-ALA/wiki/Relat%C3%B3rio).

## 🔨 Pré-requisitos <a name="install"></a>

Para executar o projeto você precisará ter instaladas as seguintes ferramentas:

### Ferramentas
- [Julia](https://julialang.org/)

### Versões das Ferramentas
- Julia (1.9.4)

## 🔧 Configuração <a name="setup"></a>
### Depois de instalar as ferramentas anteriores

1. Abra o ambiente Julia

    Abra o seu ambiente Julia, seja através da linha de comando ou do ambiente de desenvolvimento que estiver utilizando.

2. Acesse o modo de gerenciamento de pacotes

    Digite o caractere de escape `]` no prompt do Julia para acessar o modo de gerenciamento de pacotes. Isso deve mudar o prompt para indicar que você está no modo de gerenciamento de pacotes.

    ```julia
    julia> ]
    ```

3. Instale os pacotes desejados

    Para cada pacote listado abaixo
    - LinearAlgebra
    - Plots
    - Random
    - CSV
    - DataFrames
    - Clustering

    Digite o seguinte comando para instalá-lo:

    ```julia
    pkg> add NomeDoPacote
    ```
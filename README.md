<div align="center">

<img loading="lazy" src="https://github.com/user-attachments/assets/9e4a0523-4f7b-4476-8a75-bc8d9ed47e5b" width=800>

</div>

<h1 align="center"> Previsão de Sobrevida de Pacientes com Câncer de Pulmão: Integração de Modelos Binário e Regressivo </h1>

### Projeto Aprendizado de Máquina, Turma 2024
### Colaboradores: Glauber Nascimento, Rafael Anis e Maria Emily Gomes  
### Aprendizado de Máquina -  Prof. Dr. Daniel Cassar

 <h4 align="center"> 
    🚧  Projeto em construção 🚧
</h4>

<h2 align="left"> 💡 Descrição </h2>

<div align="justify">
Este projeto se baseia em um conjunto de modelos preditivos para encontrar o tempo de sobrevida de pacientes com câncer de pulmão de células não pequenas. Dessa forma, foi necessário o uso de um modelo classificador binário, que prevê se o paciente foi curado ou não, ou seja, se a previsão de sobrevida é maior que 60 meses ou não, e caso não tenha sido curado, um modelo regressor, que prevê o tempo, em meses, de sobrevida deste paciente. O objetivo desse trabalho é auxiliar na urgência/intensificação de tratamento em pacientes com menos tempo de sobrevida.
</div>

<h2 align="left"> 🫁 Atributos </h2>

<div align="justify">

Os atributos usados foram inicialmente definidos com auxílio da professora Juliana Smetana, visando os principais parâmetros para a influência da sobrevida em pacientes com cancer. Além disso, alguns atributos foram selecionados pelo falor de inflação de variância (VIF), sendo os mais relevantes listados abaixo:

`Age at surgical procedure`: Idade que o paciente foi submetido ao procedimento cirúrgico.
 
`Fraction genome altered`: Fração do genoma que foi alterado.

`Met count`: Quantas metástases o paciente possui.

`Met site count`: Quantos sítios de metástase o paciente possui.

`MSI Score`: Quantidades de microssatélites instáveis que o paciente possui, resultado de problemas no reparo do DNA.

`Mutation count`: Quantas mutações o paciente possui.

`TBM (nonsynonymous)`: Número total de mutações não sinônimas.


</div>

<h2 align="left"> 🏹 Target </h2>

<div align="justify">

Para o modelo classificador binário:
 
`Curado`: Se o paciente irá ser curado do cancer em menos de 5 meses.

Para o modelo regressor floresta aleatória:

`Sobrevida`: Tempo, em meses, que o paciente irá sobreviver.

</div>


<h2 align="left"> 📔 Notebooks e arquivos do projeto </h2>

<div align="justify">

`msk_met_2021_clinical_data (1) 1.tsv`: Dataset usado no trabalho, retirado da referência 1
 
`Estudando o Target`: Neste notebook, estudamos as colunas do dataset com potencial de serem targets para a realização dos modelos. Ao ver que as colunas presentes no dataset eram organizadas de forma diferente do que os modelos buscam, novas colunas foram criadas.

`Escolha de hiperparâmetros e atributos para o modelo classificador`: Neste notebook, buscamos, por meio do Optuna, os melhores hiperparâmetos e atributos para o modelo classificador binário, onde ele prevê se o paciente foi curado, ou não.

`Escolha de  hiperparâmetros e atributos para o modelo regressor`: Neste notebook, buscamos, por meio do Optuna, os melhores hiperparâmetos e atributos para o modelo regressor, onde ele prevê o tempo de sobrevida do paciente, em meses. <br> 

`Predição de sobrevida - A história`: Neste notebook, apresentamos os melhores modelos treinados e teste de aplicação em um grupo pertencente no limiar de meses entre 53 e 62.


</div>

<h2 align="left"> 🤖 Modelos Usados </h2>

<div align="justify">

`Baseline`: Este modelo é usado como uma forma de comparação aos modelos mais complexos, sendo a média ou mediana, em casos numéricos e a moda em variáveis cateóricas.

`Classificador binário Floresta Aleatória`: Este modelo classifica os dados em Curados e Não-Curados. 

`Regressor Floresta Aleatória`: Este modelo retorna o target do tempo de sobrevida, em meses, do paciente. Este modelo possui diversas árvores de decisão, que organiza os dados através da semelhança em um atributo, e é aleatório pois a formação dessas árvores depende da amostragem dos atributos.

</div>

<h2 align="left"> 🧰 ferramentas Usadas </h2>

<div align="justify">

`Optuna`: Esta ferramenta é extremamente útil para encontrar os melhores hiperparâmetros dos modelos desenvolvidos. Pela busca adaptativa, essa ferramenta altera esses hiperparâmetros automaticamente, podendo, assim, encontrar o melhor modelo. 3

`Fator de Inflação de Variância (VIF)`: É uma ferramenta para a análise da multicolinearidade dos atributos, sendo importante para filtrar os que apresentam alta colinearidade. A multicolinearidade influencia negativamente para a performance do modelo, pois atrapalha a interpretação dos coeficientes, aumentando o erro posterior. 4

`Root Mean Square Error (RMSE)`: Métrica usada para avaliar um modelo de regressão, no nosso trabalho a floresta aleatória. Sendo calculada pela raiz quadrada da média dos quadrados dos erros, oferecendo uma medida entre os valores preditos e verdadeiros.

`Acurácia`: métrica usada na classificação de problemass binários, que se baseia nos exemplos que foram corretamente identificados.

`Precisão`: métrica usada na classificação de problemass binários, que se baseia nos exemplos que foram classificados com rótulo positivo e foram corretamente identificados.

`Sensibilidade`: métrica usada na classificação de problemass binários, que se baseia nos exemplos que possuem um rótulo positivo e foram corretamente identificados.

</div>

<h2 align="left"> 📁 Acesso ao projeto </h2>

<div align="justify">

Você pode acessar o código pelo github ou, preferencialmente, baixá-lo.

</div>

<h2 align="left"> 🛠️ Abrir e rodar o projeto </h2>

<div align="justify">

Depois de baixar o projeto você deve abrí-lo no Jupyter Notebook/VS code

</div>

<h2 align="left"> 📓 Linguagens e programas usados </h2>

<div align="justify">

`Python`, `Jupyter Notebook`, `VS Code`, `Matplotlib`, `Scikit Learn`, `Numpy`, `Pandas` 

</div>

<h2 align="left"> 📖 Referências </h2>

<div align="justify">

1.  Nguyen, B. et al. Genomic characterization of metastatic patterns from prospective clinical sequencing of 25,000 patients. Cell 185, 563-575.e11 (2022).
2.  Daniel Cassar, Material de Aula, disciplina: Aprendizado de Máquina. 2024 
3.  Optuna - A hyperparameter optimization framework. Disponível em: https://optuna.org/
4.  Yemulwary, S. Feature Selection Techniques. Disponível em: https://medium.com/analytics-vidhya/feature-selection-techniques-2614b3b7efcd

</div>

<h2 align="center"> :octocat:  Autores </h2>

<div align="center">
 
| [<img loading="lazy" src="https://github.com/user-attachments/assets/e314fef8-e638-40ce-8ae1-8c7dab89b176" width=115><br> <sub>Rafael Anis </sub>](https://github.com/RafaelShaikhzadeh)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/3980352415504306)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/rafael-anis-shaikhzadeh-santos-a58843224/) |  [<img loading="lazy" src="https://github.com/user-attachments/assets/421a946a-dd10-4477-8f3f-e1a277d997b0" width=115><br><sub>Glauber Nascimento de Oliveira</sub>](https://github.com/Glaubernaoli)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/0913262665776521)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/glauber-naoli/) |  [<img loading="lazy" src="https://github.com/user-attachments/assets/40518e6c-b75f-496a-8fce-f5c4c1cb2684" width=115><br><sub> Maria Emily Nayla</sub>](https://github.com/MEmilyGomes)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/9482558334105708)<br> [<sub>Linkedin</sub>]() |
| :---: | :---: | :---: |

</div>

<h2 align="center"> 👓  Orientação </h2>

<div align="center">
 
| [<img loading="lazy" src="https://github.com/user-attachments/assets/463d4753-7fa4-4a42-aa54-409e4150bb51" width=115><br> <sub>Daniel R. Cassar </sub>](https://github.com/drcassar)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/1717397276752482) | 
| :---: | 

</div>

<h3 align="center"> 
 
`Contribuições` - Todos os autores construíram o código juntos e também atuaram como revisores do trabalho apresentado.
 
 </h3>
 
<h5 align="center"> 
 
 `Glauber Nascimento` escreveu esse documento, revisado por `Rafael Anis` e `Maria Emily Gomes` 
 
 </h5>

<div align="center">
 
<img loading="lazy" src="https://github.com/user-attachments/assets/c4434633-7e0c-4f19-9fa3-4c4c64e35a46" width=800>

</div>


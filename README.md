<div align="center">

<img loading="lazy" src="https://github.com/user-attachments/assets/9e4a0523-4f7b-4476-8a75-bc8d9ed47e5b" width=800>

</div>

<h1 align="center"> Previsão de Sobrevida em Câncer de Pulmão: Integração de Modelos Binários e Regressivos </h1>

### Projeto Aprendizado de Máquina, Turma 2024
### Colaboradores: Glauber Nascimento, Rafael Anis e Maria Emily Gomes  
### Aprendizado de Máquina -  Prof. Dr. Daniel Cassar

 <h4 align="center"> 
    🚧  Projeto em construção 🚧
</h4>

<h2 align="left"> 💡 Descrição </h2>

<div align="justify">
Este projeto se baseia em um conjunto de modelos preditivos para encontrar o tempo de sobrevida de pacientes com câncer de pulmão de células não pequenas. Dessa forma, foi necessário o uso de um modelo classificador binário, que prevê se o paciente foi curado ou não, e caso não tenha sido curado, um modelo regressor, que prevê o tempo, em meses, de sobrevida deste paciente. O objetivo desse trabalho é auxiliar na urgência/intensificação de tratamento em pacientes com menos tempo de sobrevida.
</div>

<h2 align="left"> 📔 Notebooks e arquivos do projeto </h2>

<div align="justify">

`msk_met_2021_clinical_data (1) 1.tsv`: Dataset usado no trabalho, retirado da referência[<sub>1</sub>](10.1016/j.cell.2022.01.003)<br>
 
`Estudando o Target`: Neste notebook, estudamos o dataset escolhido para a realização dos modelos. quais colunas usaremos como atributos e qual target escolhido.

`Escolha de hiperparâmetros e atributos para o modelo classificador`: Neste notebook, buscamos, por meio do Optuna, os melhores hiperparâmetos e atributos para o modelo classificador binário, onde ele prevê se o paciente foi curado, ou não.

`Escolha de  hiperparâmetros e atributos para o modelo regresor`: Neste notebook, buscamos, por meio do Optuna, os melhores hiperparâmetos e atributos para o modelo regressor, onde ele prevê o tempo de sobrevida do paciente, em meses. <br> 

`Predição de sobrevida - A história`: Neste notebook, apresentamos os melhores modelos treinados e teste de aplicação em um grupo pertencente no limiar de meses entre 53 e 62.


</div>

<h2 align="left"> 🤖 Modelos Usados </h2>

<div align="justify">

`Classificador binário Floresta Aleatória`: Este modelo classifica os dados em Curados e Não-Curados. EXPLICAR COMO FUNCIONA QUANDO DECIDIR

`Floresta Aleatória Regressora`: Este modelo retorna o target do tempo de sobrevida, em meses, do paciente. Este modelo possui diversas árvores de decisão e é aleatório pois a fomração dessas árvores depende da amostragem dos atributos.

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
 
#### 1.  Nguyen, B. et al. Genomic characterization of metastatic patterns from prospective clinical sequencing of 25,000 patients. Cell 185, 563-575.e11 (2022).
#### 2.  Daniel R. Material de Aula, disciplina: Aprendizado de Máquina. 2024
#### 3. 
#### 4.   

</div>

<h2 align="center"> :octocat:  Autores </h2>

<div align="center">
 
| [<img loading="lazy" src="https://github.com/user-attachments/assets/e314fef8-e638-40ce-8ae1-8c7dab89b176" width=115><br> <sub>Rafael Anis </sub>](https://github.com/RafaelShaikhzadeh)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/3980352415504306)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/rafael-anis-shaikhzadeh-santos-a58843224/) |  [<img loading="lazy" src="https://github.com/user-attachments/assets/421a946a-dd10-4477-8f3f-e1a277d997b0" width=115><br><sub>Glauber Nascimento de Oliveira</sub>](https://github.com/Glaubernaoli)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/0913262665776521)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/glauber-naoli/) |  [<img loading="lazy" src="https://github.com/user-attachments/assets/40518e6c-b75f-496a-8fce-f5c4c1cb2684" width=115><br><sub> Maria Emily Nayla</sub>](https://github.com/MEmilyGomes)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/9482558334105708)<br> [<sub>Linkedin</sub>]() |
| :---: | :---: | :---: |

</div>


 #### `Contribuições` - Todos os autores construíram o código juntos e revisão geral.
 ##### `Glauber Nascimento` escreveu esse documento, revisado por `Rafael Anis` e `Maria Emily Gomes`

<div align="center">
 
<img loading="lazy" src="https://github.com/user-attachments/assets/c4434633-7e0c-4f19-9fa3-4c4c64e35a46" width=800>

</div>


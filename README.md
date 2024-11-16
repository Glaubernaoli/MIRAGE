![ ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/bcfc56a4-b124-4988-88b4-e860cb438f27)

<h1 align="center"> MIRAGE - Projeto Aprendizado de Máquina 2024.2 </h1>

### Projeto Aprendizado de Máquina, Turma 2024
### Colaboradores: Glauber Nascimento, Rafael Anis e Maria Emily Gomes  
### Aprendizado de Máquina -  Prof. Dr. Daniel Cassar
 <h4 align="center"> 
    🏁  Projeto concluído 🏁
</h4>

## 💡 Descrição
### Modelo preditivo do tempo de sobrevida de pacientes com câncer de pulmão de células não pequenas.

## 🔨 Funcionalidades do projeto
### `Genome_identifier` - Recebe uma sequência de nucleotídeos, se possui Timina e se é uma fita negativa de RNA. Retorna os aminoácidos correspondentes e os gráficos.

### `Trancrição`: Caso o códon possua Timina, identifique-o e ele será transcrito para Uracila.

### `Contagem de aminoácidos em uma sequência de nucleotídeos`: Através de uma lista com os nucleotídeos escolhidos, o código conta, respeitando os codons de iníciação e de parada, os aminoácidos presentes nessa lista.<br> 

### `Plotagem de gráficos quantitativos`: Um gráfico em barras é plotado, com os dados obtidos na contagem de aminoácidos, comparando a quantidade de todos os aminoácidos presentes.

### `Plotagem de gráficos quantitativos`: Um gráfico de pizza é plotado para mostrar a quantidade de aminoácidos com a mesma característica.

## 🪛 Funcionalidades embutidas

### `tratamento_str` - Recebe como argumento uma string. Retorna sem números, espaços e os caracteres maiúsculos
### `neg_transcription` - Recebe com argumento uma fita de rna negativa. Retona uma positiva
### `onde_esta_aug` - Recebe como argumento uma sequência de nucleotídeos e se DNA = True, ele troca as Timinas por Uracilas. Retorna a sequência de RNA a partir do códon de início `AUG`.
### `id_aminoacidos` - Recebe uma sequência de códons como argumento. Retorna uma sequência de aminoácidos.
### `ocorencias_aminoacidos` - Recebe uma sequência de aminoácidos. Retorna uma biblioteca com a quantidade de vezes que um aminoácidos apareceu.
### `grafico_ocorrencias` - Recebe o dicionário com as ocorrências de cada aminoácido. Retorna um gráfico interativo com os dados.

## 📁 Acesso ao projeto

### Você pode acessar o código pelo github ou, preferencialmente, baixá-lo.

## 🛠️ Abrir e rodar o projeto

### Depois de baixar o projeto você deve abrí-lo no Jupyter Notebook

## 📓 Linguagens e programas usados 

#### `Python`, `Jupyter Notebook`, `Plotly`, `Matplotlib`, `Datetime`
##
## 📖 Referências
#### 1.  ALURA. Como escrever um bom README para seu projeto no GitHub. Disponível em: https://www.alura.com.br/artigos/escrever-bom-readme. Acesso em: 11 jun. 2024.
#### 2.  ROCKETSEAT. Como fazer um bom README. Disponível em: https://blog.rocketseat.com.br/como-fazer-um-bom-readme/. Acesso em: 11 jun. 2024.
#### 3.  PLOTLY Technologies Inc. Python API reference for Plotly. Disponível em: https://plotly.com/python/. Acesso em: 18 jun. 2024.
#### 4.  OPENAI. ChatGPT (versão de 18 de junho). Disponível em: https://www.openai.com/chatgpt. Acesso em: 18 jun. 2024. 
##  :octocat:  Autores


| [<img loading="lazy" src="https://github.com/user-attachments/assets/e314fef8-e638-40ce-8ae1-8c7dab89b176" width=115><br> <sub>Rafael Anis </sub>](https://github.com/RafaelShaikhzadeh)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/3980352415504306)<br> [<sub>Linkedin</sub>]() |  [<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/ecbf1a63-69ba-450a-bb1d-770450b17189" width=115><br><sub>Glauber Nascimento de Oliveira</sub>](https://github.com/Glaubernaoli)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/0913262665776521)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/glauber-naoli/) |  [<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172424999/b5e432b6-bf0c-42a1-88c3-68df3c7d7545" width=115><br><sub>Enzo Januzzi</sub>](https://github.com/EnzoJanuzzi)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/1031555112242239)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/enzo-januzzi-xavier-9063842b0/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) |
| :---: | :---: | :---: |

 #### `Contribuições` - Todos os autores construíram o código juntos, quando não coletivamente, atuávamos na revisão do código, e os gráficos também.
 ##### `Glauber Nascimento` escreveu esse documento, revisado por `Gabriel Viégas` e `Enzo Januzzi`

![ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/6c9216ea-0cdb-4dac-aac5-445d505b2804)



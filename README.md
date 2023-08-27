# Teste Analista de Dados

Neste repositório está contido:
* Um Jupyter Notebook com a resposta das perguntas de negócio, para validação dos dados
* Um arquivo com o código do ETL em Python
* Uma pasta vazia com o mesmo nome da utilizada no ETL. Para acessar esses dados, basta este [link aqui](https://download.inep.gov.br/microdados/microdados_enem_2020.zip), colocar o arquivo zip na pasta e executar o arquivo etl.py

Além dos arquivos deste repositório, alguns outros materiais estão disponíveis online através destes links:
* [A apresentação do projeto](https://download.inep.gov.br/microdados/microdados_enem_2020.zip)
* [O dicionário dos dados](https://docs.google.com/spreadsheets/d/1QPtz9L1vfqMQKekWjR8A0J_J2oRqf_O-qIzV7-AEecc/edit?usp=sharing)
* [A modelagem](https://dbdiagram.io/d/64e9f3fa02bd1c4a5e72a887)
* [As dimensões](https://docs.google.com/spreadsheets/d/1gfxF0cSaxZIC1XwmGFdgkERwrZkiDZwEGFsA-s-hecw/edit#gid=0)
* [Pasta no Drive com arquivos do projeto](https://drive.google.com/drive/folders/1bytHXoY6qq7znJPIgNXPoH6EdGRWdOTX?usp=sharing)
* [Arquivo Power BI para download](https://drive.google.com/file/d/11o7PEQveftkjm5kt3yIDUnWow_Gea-aF/view?usp=drive_link) Esta Visualização dos dados ainda precisa de ajustes e remoção de algumas medidas e tratamentos no Power Query. Para carregar as dimensões, basta logar com uma conta Google.  

## Algumas imagens do projeto:

### Dicionário da Tabela Fato:
![Dicionario de Dados](src\Dicionario.png) 

### Modelagem dos Dados
![Modelagem dos Dados](src\Modelagem.png)

### Visualização do Dashboard
![Visualização](src\Visualização_Dashboard.png)



---
# Teste Analista de Dados
Critérios avaliadas:
- Uso de Funções DAX
- Documentação das medidas
- ETL
- Modelagem dimensional dos dados

### Desejáveis
- Esquema Estrela
- Criação de visuais com indicadores além dos requisitados.
- SQL (Caso deseje modelar os dados em algum banco)


### Steps:

1. Realizar um Fork desse projeto
2. Realizar a modelagem dimensional da base (Pode ser dentro do próprio PowerBI ou outra ferramenta de ETL)
    - A base está disponível para download [clicando aqui](https://download.inep.gov.br/microdados/microdados_enem_2020.zip).
    - Após descompactar a paste, o Arquivo com a base encontra-se no diretório microdados_enem_2020/DADOS/MICRODADOS_ENEM_2020.csv
    - A documentação necessária sobre os campos da base está disponível nos demais diretórios dentro da pasta descompactada.
4. Disponibilizar o link do seu repositório para posterior avaliação


### Levantar Indicadores
#### Responder às seguintes perguntas:
1. Qual a escola com a maior média de notas?
2. Qual o aluno com a maior média de notas e o valor dessa média?
3. Qual a média geral?
4. Qual o % de Ausentes?
5. Qual o número total de Inscritos?
6. Qual a média por disciplina?
7. Qual a média por Sexo?
8. Qual a média por Etnia?

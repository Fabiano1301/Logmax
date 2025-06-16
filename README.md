# Aprendizado por Projeto Integrador (API)

Template para os projetos do curso de graduação em Logística, ensinando na utilização do repositório digital "GitHub". 

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos 

# Índice
* [Projeto](#projeto-template)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Sprints](#Sprints)
* [Burndown](#Burndown)
* [Backlog do produto](#Backlog-do-produto)

# Projeto (API) 
Descrição da demanda realizada pelo parceiro acadêmico.

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Cristovão jr    |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joaomarcosoliveiraa) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoaoM-py)              |
| Scrum Master  | Fabiano Almeida |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/mariagabrielareis/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/MariaGabrielaReis)     |
| Team Member   | João Paulo             |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-nepomuceno-04943720a/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Nepoun)        |
|  Team Member  | João Vitor               |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/caio-vitor-c1/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/CaioVitorDias1)        |
|  Team Member  | Ribamar  Barros              |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-camargo-915452196/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GabrielCamargoL)   |
|  Team Member  | Willian Pierre     |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gioliveirass) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gioliveirass)          |

# Objetivo do Projeto
Este projeto tem como objetivo criar um dashboard em Power BI para análise de dados de Importações que ocorreram entre os anos de 2023 e 2024 no estado de São Paulo, utilizando dados abertos forencidos pelo Comexstat, criando uma backend em Python para filtrar e análisar esses dados, e com isso ajudar a desenvolver algumas habilidades como:  

* Trabalho em grupo;
* Organizar e estruturar as informações;
* Fazer uma divisão justa das tarefas;
* Documentar tudos via GitHub;
* Desenvolver Soft e Hard Skills.

## Tecnologias Utilizadas

 ### Tecnologias Específicas/Apoio
 - Jira
 - GitHub
 - Slack
 - Google Colab
  
 ### Tecnologias da Informação
 - Python3+
 - PowerBI

  

# Backlog do produto
- [x] Como cliente, quero conseguir segmentar por municípios para conseguir buscar quais realizam importações com maior valor agregado;
- [x] Como cliente, quero conseguir aplicar um filtro de item para identificar quais municípios mais importam eles;
- [x] Como cliente, quero conseguir ranquear os produtos com maior valor agregado importados, para identificar possíveis mercados em alta;
- [x] Como cliente, quero uma visualização gráfica de evolução histórica da balança comercial dos municípios para identificar pontos altos e baixo;
- [ ] Como usuário, quero conectar todas as fontes de dados através de um banco de dados em Python3+ para conseguir manipular toda a quantidade de dados;
- [ ] Como usuário, quero relacionar as tabelas do banco de dados para conseguir ter uma melhor visualização dos municípios e produotos exportados;
- [ ] Como cliente, quero que seja desenvolvido uma backend em Python3+ para conseguir localizar e filtrar os dados de forma mais dinâmica;
- [ ] Como cliente, quero que seja feito um estudo de sazonalidade para que seja possível identificar períodos de maior em menos movimento das exportações;
- [ ] Como cliente, quero que seja mostrado a diversificação dos produtos e quais municípios concentram suas exportações em poucos produtos e quais diversificam mais;
- [ ] Como cliente, quero que sejam feitas projeções futuras com base nas tendências históricas do período analisado;

## Sprint 1
Na primeira Sprint, o cliente aprovou o backlog para as seguintes tarfas:
- [x] Gerar um PowerBI que conseguisse seguimentar por municipios;
- [x] Que conseguisse filtrar por itens importados;
- [x] Que ranqueasse esses itens por municipio;
- [x] Que mostrasse uma evolução através do tempo dessas importações;

- Nesse primeiro momento, para conseguir trabalhar o layout do dashboard e entender um pouco mais como funcionariam a união dos dados no Python, através do bloco de notas, selecionamos arbitrariamente um período aleatório para criar uma planilha mais leve que pudessemos trabalhar sem problemas no Excel e no Power BI, com cerca de 200 linhas, e criamos o seguinte dashboard.

![image](https://github.com/user-attachments/assets/42bbbcba-c6f5-4022-a743-f09c66991114)

- Não fizemos a alteração dos nomes dos produtos nem dos municípios, e o grafico representa apenas uma pequena fração do período de análise do projeto.


## Sprint 2
Nessa Sprint 2, conseguimos validar com o cliente as tarefas para conectar e relacionar os dados através da kinguagem de programação Python, utilizando a ferramenta Google Colab para desenvolver o código.
- [x] Conectar todas as fontes de dados através de um banco de dados em Python3+ para conseguir manipular toda a quantidade de dados;
- [x] Relacionar as tabelas do banco de dados para conseguir ter uma melhor visualização dos municípios e produotos exportados;

- Nesse primeiro momento, criamos a planilha "Filtro" onde nós concatenamos as planilhas com as importações de 2023 e 2024, além de aplicar um filtro para que mostrasse apenas as importações feitas no Estado de São Paulo.

![image](https://github.com/user-attachments/assets/30370806-498a-46f5-abaa-d380e443944f)
![image](https://github.com/user-attachments/assets/6faa1c88-240f-4c4f-8d85-03dcc0ffe104)
![image](https://github.com/user-attachments/assets/15a118cb-3280-45ff-9cd6-4dfeea22c310)
![image](https://github.com/user-attachments/assets/a1cad5fd-e5e5-477f-a8b9-61e0df764de7)
![image](https://github.com/user-attachments/assets/5967e6ec-c044-49fc-b50b-703a96a4cbd3)
![image](https://github.com/user-attachments/assets/c68c47e6-9b75-40c8-b710-aba9063de9b6)
![image](https://github.com/user-attachments/assets/3f3ec7bd-7e85-4801-baa8-05a6a9d9464f)
![image](https://github.com/user-attachments/assets/a7e00f1a-fc98-4a53-bb52-1f113874b901)

- Já nesse segundo momento, como os códigos da primeira etapa estavam um pouco confusos, decidimos começar de novo, mas importando a planilha onda já haviamos progredido ao invés de iniciar do 0.
- Feito isso, conseguimos fazer o Merge das informações sobre municípios, paises e produtos na planilha, e também criamos uma nova coluna para alocar o "Valor Agregado" que será utilizado futuramente para compor o ranking no dashboard.
- Além disso, nós também removemos os resultados negativos e nulos dessa nova coluna, para evitar distroções indesejadas no gráfico.

![image](https://github.com/user-attachments/assets/1b62b7fe-1b8c-4df1-8757-65c7b4fe8b39)
![image](https://github.com/user-attachments/assets/4352d59f-a193-43c9-b8b6-bf421b89c034)
![image](https://github.com/user-attachments/assets/ffce2661-447f-4287-920f-f84f5822dbd3)
![image](https://github.com/user-attachments/assets/242385cf-5800-4b5e-a9b4-92de58285008)
![image](https://github.com/user-attachments/assets/0f46ca1a-ef2b-466e-be70-0ca1bf255a90)
![image](https://github.com/user-attachments/assets/43ffea9f-163f-43ad-b160-5438b32d8fe0)
![image](https://github.com/user-attachments/assets/917dc8eb-48d2-4a68-b789-b61223a550dc)
![image](https://github.com/user-attachments/assets/15c7c741-910f-4f63-8266-4724af4ef0fb)
![image](https://github.com/user-attachments/assets/7b027a43-7b39-43db-8dbc-1630fd04193b)
![image](https://github.com/user-attachments/assets/eaac2bba-c35c-4dd4-b8d9-98a8570c0231)

## Sprint 3
Na Sprint 3 conseguimos mudar a dashboard conforme as necessidades do cliente, tambem estamos finalizando o relatorio do projeto 
![WhatsApp Image 2025-06-02 at 09 19 28](https://github.com/user-attachments/assets/2cc64b57-65b1-4578-8586-ddc3b7c9f28e)
![WhatsApp Image 2025-06-02 at 09 19 28 (1)](https://github.com/user-attachments/assets/e0e816b1-d937-473c-981f-70fb9f213b3c)
![WhatsApp Image 2025-06-02 at 09 19 29](https://github.com/user-attachments/assets/30d02f97-16c8-48ad-8280-bbc72364d5e9)
![WhatsApp Image 2025-06-02 at 09 19 29 (1)](https://github.com/user-attachments/assets/89e838f0-f501-4e4d-98f5-3a3dea8fd1b8)

## Sprint 4
Nessa sprint realizamos uma correção na base de dados, conforme solicitado pelo Cliente
![image](https://github.com/user-attachments/assets/bb1fb358-c0f2-4d30-b4da-3ca4d8a6340d)
dados corrigidos no pyton 
![image](https://github.com/user-attachments/assets/dd1b4dc2-a4ca-47bd-92e6-fded495036e5)

![image](https://github.com/user-attachments/assets/8d3a0ac1-e63b-4628-a7cc-36c7d3fda7a0)

# Registro das Sprints

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
|01 | 31/03/2025 | Feito | [MVP](https://) | 
|02|  05/05/2025| Feito|[MVP](https://) | 
|03| 02/06/2025 | Feito|[MVP](https://) | 
|04| 17/06/2025 | Feito|[MVP](https://)  | 
|Feira de Soluções|17/06/2025 |Feito |[MVP](https://) | 
# projeto-de-munic-pios

![image](https://github.com/user-attachments/assets/add2936f-fc6e-4b39-803a-2411534d17b0)

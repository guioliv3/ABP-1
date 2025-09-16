
# ABP 1º Semestre DSM

# Desenvolvimento de um website para o laboratório de Sensoriamento Remoto Agrícola do INPE – AgriRS Lab


<p align="center">
      <img src="" alt="" width="">
      <h2 align="center"> NightHawks</h2>
</p>

<p align="center">
  | <a href ="#desafio"> Desafio</a>  |
  <a href ="#solucao"> Solução</a>  |   
  <a href ="#backlog"> Backlog do Produto</a>  |
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#sprint"> Cronograma de Sprints</a>  |
  <a href ="#tecnologias">Tecnologias</a> |
  <a href ="#manual">Manual de Instalação</a>  | 
  <a href ="#equipe"> Equipe</a> |
</p>

> Status do Projeto: Início 15/09/2025   
>
> Relatório de Testes: [PDF] 📊
>
> Pasta de Documentação: [Link] 📄
> 
> Video do Projeto:  [Youtube] 📽️

## 🏅 Desafio <a id="desafio"></a>

A criação de um website para o Laboratório de Sensoriamento Remoto Agrícola do INPE (AgriRS
Lab) tem como propósito principal centralizar as informações importantes do laboratório, ampliar
a visibilidade do laboratório e facilitar o acesso do público às pesquisas, projetos e iniciativas. Além
disso, seria importante para divulgar informações importantes, como os integrantes da equipe,
nossas áreas de atuação, publicações científicas, oportunidades de trabalho e formas de contato.
Isso ajudaria a manter nossas atividades e descobertas científicas atualizadas para a comunidade e
promoveria a divulgação do laboratório para quem quiser conhecer ou se aproximar do nosso
trabalho.


## 🏅 Solução <a id="solucao"></a>

<n> ALTERAR OU PENSAR EM ALGO PARA SOLUÇÃO </n>

---

## 📋 Backlog do Produto <a id="backlog"></a>
--- ANALISAR QUAL SERÁ O MÉTODO DE USO DO BACKLOG, VIA LINK DENTRO DO GIT OU EXTERNO PELO EXCEL --
| Rank | Prioridade | User Story                                                                                                                                                                                                     | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :------------------: | :----: |
|   1  |    Alta    | Como usuário, quero uma interface para inserir um prompt, para que eu possa enviá-lo às LLMs e obter suas respostas                                                                                            |            |       |                  |       |
|   2  |    Alta    | Como usuário, eu quero enviar um prompt para dois modelos de IA simultaneamente, para que eu possa avaliar suas respostas posteriormente.                                                                      |            |       |               |       |
|   3  |    Alta    | Como usuário, eu quero visualizar as respostas das LLMs de forma clara e acessível, para que eu possa analisá-las em critérios.                                                                                |            |      |                  |       |


---

## 🏃‍ DoR - Definition of Ready <a id="dor"></a>

* User Stories com **Critérios de Aceitação**
* Subtarefas divididas **a partir das US**
* Design no **Figma**
* Modelagem do **Banco de Dados**
* Diagrama de **Rotas**
* Banco de Dados **Vetorizado** do Cliente

## 🏆 DoD - Definition of Done <a id="dod"></a>

* Manual de Usuário
* Manual da Aplicação
* Documentação da API (Application Programming Interface)
* Código completo
* Vídeos de cada etapa de entrega

---

## 📅 Cronograma de Sprints <a id="sprint"></a>

| Sprint          |    Período    | Documentação                                     |
| --------------- | :-----------: | ------------------------------------------------ |
| 🔖 **SPRINT 1** | 10/03 - 30/03 | [Sprint 1 Docs](./docs/processo/sprints/sprint-1/README.md) |
| 🔖 **SPRINT 2** | 07/04 - 27/04 | [Sprint 2 Docs](./docs/processo/sprints/sprint-2/README.md) |
| 🔖 **SPRINT 3** | 05/05 - 25/05 | [Sprint 3 Docs](./docs/processo/sprints/sprint-3/README.md) |

## 💻 Tecnologias <a id="tecnologias"></a>

<h4 align="center">
 <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
 <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"></a>
 <a href="https://github.com/"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
 <a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/></a>
</h4>

## 📖 Manual de Instalação <a id="manual"></a>

### 🛠 Pré-requisitos

- Git ([Download](https://git-scm.com/downloads))

- Python 3.9+ ([Download](https://www.python.org/downloads/))

- Node.js 16+ ([Download](https://nodejs.org/en/download))

- Poetry (opcional para o backend) ([Download](https://python-poetry.org/))

---

### 1. Clonar o Repositório Principal

```bash
git clone --recurse-submodules https://github.com/BuzzTech-API/API_ADS_6SEMESTE_2025.1.git
cd API_ADS_6SEMESTE_2025.1
```

> **Observação:** Se já tiver clonado sem os submódulos, execute:

```
git submodule update --init --recursive
```

---

### 2. Configuração do Backend (auxia-backend)

**1° Adicione as variáveis no .env**

**2° Inicialize o Banco de dados MongoDB no localhost:**

**3° Coloque a base de dados vetorizada ./client dentro da raíz do backen:**

**4° Instale e Inicie a aplicação:**

**Opção A: Com Poetry**

```bash
cd ./auxia-backend
poetry shell
poetry install
make run
```

**Opção B: Com Ambiente Virtual Python**

```bash
cd ./auxia-backend
python3 -m venv venv
source venv/bin/activate # se você usa linux
venv/Scripts/activate 	 # se você usa windows
pip install -r requirements.txt
fastapi dev ./auxia/main.py
```

**Saída Esperada:**
<br>
Servidor rodando em `http://localhost:8000` (acesse `http://localhost:8000/docs` para a UI do Swagger).

---

### 3. Configuração do Frontend (auxia-frontend)

```bash
cd ../auxia-frontend/auxia
npm install
npm run dev
```

**Saída Esperada:**
<br>
Frontend rodando em `http://localhost:5173`.

## 🎓 Equipe <a id="equipe"></a>

<div align="center">
  <table>
    <tr>
      <th>Membro</th>
      <th>Função</th>
      <th>Github</th>
      <th>Linkedin</th>
    </tr>
    <tr>
      <td>Nikolas Furuta</td>
      <td>Product Owner</td>
      <td><a href="https://github.com/nikolasfurutadev"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Victor Coutinho</td>
      <td>Scrum Master</td>
      <td><a href="https://github.com/Vitaixs"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Allan Ramos</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Allan-ramos122"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/isaque-elis-da-silva-2a4087226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Gianluca Lourenço</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Duraxxi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/joice-aparecida-581226250/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Guilherme Henrique</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/guioliv3"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="http://linkedin.com/in/jonas-alves"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Lucas Cobra</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/LucasCobraFatec"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Lucas Cecon</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/lucas-cecon"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
        <tr>
      <td>Thiasley </td>
      <td>Desenvolvedor</td>
      <td><a href=""><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
  </table>
</div>

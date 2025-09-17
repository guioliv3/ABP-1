# ABP 1º Semestre DSM

# Desenvolvimento de um website para o laboratorio de Sensoriamento Remoto Agrícola do INPE -AgriRS Lab 

# Documentação - Sprint 1

<p align="center">
      <img src="../../img/nhdevlogo.png" alt="logo da Nighthawks Tech" width="200">
      <h2 align="center"> NightHawks</h2>
</p>

<p align="center">
  | <a href ="#desafio"> Desafio</a>  |
  <a href ="#us"> Backlog</a>  |   
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#equipe"> Equipe</a> |
</p>

> Status da Sprint: Em andamento ⏳


##  Desafio <a id="desafio"></a>
-- **ATUALIZAR**--

Desenvolver a Home Page responsiva de um site institucional do INPE, incluindo componentes principais reutilizáveis, seguindo um design fornecido.

##  Backlog e progresso <a id="us"></a>

| Backlog ID | Tipo do item | Descrição                                      | Especifidades                                                                                                                                                                                                                                                                                                    | Pontuação | Status   | Código | Tecnologias utilizadas | Allan     | Gianluca  | Guilherme | Lucas Cecon | Lucas Cobra | Nikolas   | Victor    | Thiasley  |
|------------|--------------|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|----------|--------|------------------------|-----------|-----------|-----------|-------------|-------------|-----------|-----------|-----------|
| RNF01      | DESIGN       | SELEÇÃO DE COR BASE DO SITE                    | Identidade visual com referencias de cor e designer                                                                                                                                                                                                                                                              | 1         | Relizado | DD-001 | ADOBE COLOR, FIGMA     |           |           |           |             | Atribuído   |           | Atribuído |           |
| RNF01      | DESIGN       | CRIAÇÃO PAGINA BASE                            | Criar página base com header e footer que serão utilizados como padrão para todas as páginas seguintes                                                                                                                                                                                                           | 3         | Relizado | DD-002 | FIGMA                  | Atribuído | Atribuído | Atribuído | Atribuído   | Atribuído   | Atribuído | Atribuído | Atribuído |
| RNF01      | FRONTEND     | CRIAÇÃO PAGINA BASE                            | Criar uma página base com o header e footer que servirá de padrão para todas as páginas seguintes                                                                                                                                                                                                                | 5         | 30.00%   |        |                        |           |           | Atribuído |             |             |           | Atribuído |           |
| RF01       | DESIGN       | CRIAÇÂO DE UMA PAGINA HOME                     | Criar uma página home OBRIGATÓRIAMENTE contendo cards de notícias, projeto, publicações ou outras atualizações, colaboradores, descrições sobre o INPE e o laboratório e previews das demais páginas.                                                                                                            | 5         | 70.00%   | DD-003 | FIGMA                  |           |           |           |             | Atribuído   |           |           |           |
| RF03       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE MEMBROS               | Criar uma página referente aos membros do laboratório, descrevendo tambem as respectivas àreas de atuação, nome, foto, função e breve descrição.                                                                                                                                                                 | 5         | 70.00%   | DD-004 | FIGMA                  |           |           |           | Atribuído   |             |           |           |           |
| RF02       | DESIGN       | CRIAÇÃO DE UMA PÁGINA "SOBRE"                  | Criar uma página descrevendo com detalhes o laboratório, contendo OBRIGATÓRIAMENTE objetivo, foco, descrição sobre as àreas de atuação e textos explicativos                                                                                                                                                     | 3         | 90.00%   | DD-005 | FIGMA                  |           | Atribuído |           |             |             |           |           |           |
| RF04       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE VAGAS                 | Criar uma página de vagas contendo instruções sobre como se candidatar, oportunidades e parcerias estabelecidas pelo laboratório                                                                                                                                                                                 | 3         | 90.00%   | DD-006 | FIGMA                  |           |           |           |             |             | Atribuído |           |           |
| RF05       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE PROJETOS              | Criar uma página de projetos contendo OBRIGATÓRIAMENTE título, resumo, ano de início, status e equipe envolvida.                                                                                                                                                                                                 | 5         | 50.00%   | DD-007 | FIGMA                  |           |           | Atribuído |             |             |           |           |           |
| RF06       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIAS              | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | 90.00%   | DD-008 | FIGMA                  | Atribuído |           |           |             |             |           |           |           |
| RF06       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIA INDIVIDUAL    | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | 90.00%   | DD-009 | FIGMA                  |           |           |           |             |             |           | Atribuído |           |
| RF06       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE ENVIO DE NOTICIAS     | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | 20.00%   | DD-010 | FIGMA                  | Atribuído |           |           | Atribuído   |             |           |           |           |
| RF07       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE PUBLICAÇÕES           | Criar uma página de publicações contendo artigos, livros, capítulos e etc. com titúlo, revista, autores, ano e link. Além disso a página deverá ter um campo de pesquisa por palavras-chave.                                                                                                                     | 5         | 90.00%   | DD-011 | FIGMA                  |           | Atribuído |           |             |             |           |           |           |
| RF08       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE CONTATO               | Criar uma página de contato com um formulário com os campos: nome, e-mail. assunto e mensagem. Ao ser confirmado, o formulário deve enviar tudo para o email do agrislab. A página deve conter informações de contato instiucional, links para redes sociais e um mapa para a localização do laboratório no INPE | 3         | 90.00%   | DD-012 | FIGMA                  |           |           |           |             |             |           | Atribuído |           |
| RF01       | FRONTEND     | CRIAÇÂO DE UMA PAGINA HOME                     | Criar uma página home OBRIGATÓRIAMENTE contendo cards de notícias, projeto, publicações ou outras atualizações, colaboradores, descrições sobre o INPE e o laboratório e previews das demais páginas.                                                                                                            | 8         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF03       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE MEMBROS               | Criar uma página referente aos membros do laboratório, descrevendo tambem as respectivas àreas de atuação, nome, foto, função e breve descrição.                                                                                                                                                                 | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF02       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA "SOBRE"                  | Criar uma página descrevendo com detalhes o laboratório, contendo OBRIGATÓRIAMENTE objetivo, foco, descrição sobre as àreas de atuação e textos explicativos                                                                                                                                                     | 3         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF04       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE VAGAS                 | Criar uma página de vagas contendo instruções sobre como se candidatar, oportunidades e parcerias estabelecidas pelo laboratório                                                                                                                                                                                 | 3         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF05       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PROJETOS              | Criar uma página de projetos contendo OBRIGATÓRIAMENTE título, resumo, ano de início, status e equipe envolvida.                                                                                                                                                                                                 | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIAS              | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF07       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PUBLICAÇÕES           | Criar uma página de publicações contendo artigos, livros, capítulos e etc. com titúlo, revista, autores, ano e link. Além disso a página deverá ter um campo de pesquisa por palavras-chave.                                                                                                                     | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF08       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE CONTATO               | Criar uma página de contato com um formulário com os campos: nome, e-mail. assunto e mensagem. Ao ser confirmado, o formulário deve enviar tudo para o email do agrislab. A página deve conter informações de contato instiucional, links para redes sociais e um mapa para a localização do laboratório no INPE | 3         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIA INDIVIDUAL    | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE ENVIO DE NOTICIAS     | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 8         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RNF01      | DESIGN       | TIPOGRAFIA                                     | Definição de uma familia de fontes que serão usadas no projeto todo.                                                                                                                                                                                                                                             | 1         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| SETUP-01   | INFRA        | Configurar repositório                         | Criar repositório GitHub e estrutura de pastas (HTML, CSS, JS, imagens).                                                                                                                                                                                                                                         | 1         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF01       | FRONTEND     | CRIAÇÂO DE UMA PAGINA HOME - MOBILE            | Criar uma página home OBRIGATÓRIAMENTE contendo cards de notícias, projeto, publicações ou outras atualizações, colaboradores, descrições sobre o INPE e o laboratório e previews das demais páginas.                                                                                                            | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF03       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE MEMBROS  - MOBILE     | Criar uma página referente aos membros do laboratório, descrevendo tambem as respectivas àreas de atuação, nome, foto, função e breve descrição.                                                                                                                                                                 | 3         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF02       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA "SOBRE"  - MOBILE        | Criar uma página descrevendo com detalhes o laboratório, contendo OBRIGATÓRIAMENTE objetivo, foco, descrição sobre as àreas de atuação e textos explicativos                                                                                                                                                     | 3         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF04       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE VAGAS  - MOBILE       | Criar uma página de vagas contendo instruções sobre como se candidatar, oportunidades e parcerias estabelecidas pelo laboratório                                                                                                                                                                                 | 3         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF05       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PROJETOS  - MOBILE    | Criar uma página de projetos contendo OBRIGATÓRIAMENTE título, resumo, ano de início, status e equipe envolvida.                                                                                                                                                                                                 | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIAS  - MOBILE    | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF07       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PUBLICAÇÕES  - MOBILE | Criar uma página de publicações contendo artigos, livros, capítulos e etc. com titúlo, revista, autores, ano e link. Além disso a página deverá ter um campo de pesquisa por palavras-chave.                                                                                                                     | 5         | Pendente |        |                        |           |           |           |             |             |           |           |           |
| RF08       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE CONTATO  - MOBILE     | Criar uma página de contato com um formulário com os campos: nome, e-mail. assunto e mensagem. Ao ser confirmado, o formulário deve enviar tudo para o email do agrislab. A página deve conter informações de contato instiucional, links para redes sociais e um mapa para a localização do laboratório no INPE | 3         | Pendente |        |                        |           |           |           |             



##  DoR - Definition of Ready <a id="dor"></a>

|             Critério             | Descrição                                                                                                                                                           |
| :------------------------------: | ------------------------------------------------------------------------------------------------- |
|       Escopo Definido       | As páginas ou componentes que farão parte da 1ª Sprint estão listados e priorizados (ex.: página inicial, cabeçalho, rodapé, menu de navegação).           |
| Protótipo Aprovado | Layout inicial (Figma) da estrutura do site disponível para consulta. |
| Identidade Visual  | Paleta de cores, tipografia, logotipo e padrões visuais básicos aprovados e documentados.                   |
|           Estimativa de Esforço          | As histórias/tarefas planejadas foram pontuadas e são viáveis para conclusão dentro da Sprint.                    |


##  DoD - Definition of Done <a id="dod"></a>

|                 Critério                 | Descrição                                                                            |
| :--------------------------------------: | ------------------------------------------------------------------------------------ |
|     Implementação Fiel                   | Interface criada conforme protótipo.                                                 |
|     Responsividade OK                    | Funciona em desktop, tablet e mobile.                                                |
|          Revisão e Deploy                | Código revisado, aprovado e build sem erros.                                         |
|     Código Padronizado                   | Segue boas práticas e padrões do time.                                               |


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
      <td>Nikolas Furuta </td>
      <td>Product Owner</td>
      <td><a href="https://github.com/nikolasfurutadev"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/nikolasfuruta-dev/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
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
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Gianluca Loureno</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Duraxxi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Guilherme Henrique</td>
      <td>Desenvolvedor</td>
      <td><a href=""><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Lucas Cecon</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/lucas-cecon"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="s"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Lucas Cobra</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/LucasCobraFatec"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Thiasley</td>
      <td>Desenvolvedor</td>
      <td><a href=""><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
  </table>
</div>

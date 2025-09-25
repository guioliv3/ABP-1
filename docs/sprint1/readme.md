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

| Backlog ID | Tipo do item | Descrição                                             | Prioridade | Especifidades                                                                                                                                                                                                                                                                                                    | Pontuação | Status    | Código | Link | Prazo    | Atribuídos                                                                        |
|------------|--------------|-------------------------------------------------------|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|-----------|--------|------|----------|-----------------------------------------------------------------------------------|
| RNF01      | DESIGN       | SELEÇÃO DE COR BASE DO SITE                           | Urgente    | Identidade visual com referencias de cor e designer                                                                                                                                                                                                                                                              | 1         | ✅         | DD-001 |      | 16/09/25 | Lucas Cobra, Victor,                                                              |
| RNF01      | DESIGN       | CRIAÇÃO PAGINA BASE                                   | Urgente    | Criar página base com header e footer que serão utilizados como padrão para todas as páginas seguintes                                                                                                                                                                                                           | 3         | ✅         | DD-002 |      | 17/09/25 | Allan, Gianluca, Guilherme, Lucas Cecon, Lucas Cobra, Nikolas, Victor, Thiasley,  |
| RNF01      | FRONTEND     | CRIAÇÃO PAGINA BASE                                   | Urgente    | Criar uma página base com o header e footer que servirá de padrão para todas as páginas seguintes                                                                                                                                                                                                                | 5         | ✅         | DW-001 |      | 19/09/25 | Guilherme, Victor,                                                                |
| RF01       | DESIGN       | CRIAÇÂO DE UMA PAGINA HOME                            | Urgente    | Criar uma página home OBRIGATÓRIAMENTE contendo cards de notícias, projeto, publicações ou outras atualizações, colaboradores, descrições sobre o INPE e o laboratório e previews das demais páginas.                                                                                                            | 5         | ✅         | DD-003 |      | 19/09/25 | Lucas Cobra,                                                                      |
| RF03       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE MEMBROS                      | Urgente    | Criar uma página referente aos membros do laboratório, descrevendo tambem as respectivas àreas de atuação, nome, foto, função e breve descrição.                                                                                                                                                                 | 5         | ✅         | DD-004 |      | 19/09/25 | Lucas Cecon,                                                                      |
| RF02       | DESIGN       | CRIAÇÃO DE UMA PÁGINA "SOBRE"                         | Urgente    | Criar uma página descrevendo com detalhes o laboratório, contendo OBRIGATÓRIAMENTE objetivo, foco, descrição sobre as àreas de atuação e textos explicativos                                                                                                                                                     | 3         | ✅         | DD-005 |      | 19/09/25 | Gianluca,                                                                         |
| RF04       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE VAGAS                        | Urgente    | Criar uma página de vagas contendo instruções sobre como se candidatar, oportunidades e parcerias estabelecidas pelo laboratório                                                                                                                                                                                 | 3         | ✅         | DD-006 |      | 19/09/25 | Nikolas,                                                                          |
| RF05       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE PROJETOS                     | Urgente    | Criar uma página de projetos contendo OBRIGATÓRIAMENTE título, resumo, ano de início, status e equipe envolvida.                                                                                                                                                                                                 | 5         | ✅         | DD-007 |      | 19/09/25 | Guilherme,                                                                        |
| RF06       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIAS                     | Urgente    | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | ✅         | DD-008 |      | 19/09/25 | Allan,                                                                            |
| RF06       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIA INDIVIDUAL           | Urgente    | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | ✅         | DD-009 |      | 19/09/25 | Victor,                                                                           |
| RF06       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE ENVIO DE NOTICIAS            | Urgente    | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | ✅         | DD-010 |      | 19/09/25 | Allan, Lucas Cecon,                                                               |
| RF07       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE PUBLICAÇÕES                  | Urgente    | Criar uma página de publicações contendo artigos, livros, capítulos e etc. com titúlo, revista, autores, ano e link. Além disso a página deverá ter um campo de pesquisa por palavras-chave.                                                                                                                     | 5         | ✅         | DD-011 |      | 19/09/25 | Gianluca,                                                                         |
| RF08       | DESIGN       | CRIAÇÃO DE UMA PÁGINA DE CONTATO                      | Urgente    | Criar uma página de contato com um formulário com os campos: nome, e-mail. assunto e mensagem. Ao ser confirmado, o formulário deve enviar tudo para o email do agrislab. A página deve conter informações de contato instiucional, links para redes sociais e um mapa para a localização do laboratório no INPE | 3         | ✅         | DD-012 |      | 19/09/25 | Victor,                                                                           |
| RF01       | FRONTEND     | CRIAÇÂO DE UMA PAGINA HOME                            | Muito alta | Criar uma página home OBRIGATÓRIAMENTE contendo cards de notícias, projeto, publicações ou outras atualizações, colaboradores, descrições sobre o INPE e o laboratório e previews das demais páginas.                                                                                                            | 8         | ✅         | DW-006 |      | 26/09/25 | Lucas Cobra,                                                                      |
| RF03       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE MEMBROS                      | Muito alta | Criar uma página referente aos membros do laboratório, descrevendo tambem as respectivas àreas de atuação, nome, foto, função e breve descrição.                                                                                                                                                                 | 5         | ✅         | DW-002 |      | 26/09/25 | Lucas Cecon,                                                                      |
| RF02       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA "SOBRE"                         | Alta       | Criar uma página descrevendo com detalhes o laboratório, contendo OBRIGATÓRIAMENTE objetivo, foco, descrição sobre as àreas de atuação e textos explicativos                                                                                                                                                     | 3         | ✅         | DW-003 |      | 26/09/25 | Gianluca,                                                                         |
| RF04       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE VAGAS                        | Muito alta | Criar uma página de vagas contendo instruções sobre como se candidatar, oportunidades e parcerias estabelecidas pelo laboratório                                                                                                                                                                                 | 3         | 40.00%    | DW-004 |      | 26/09/25 | Nikolas,                                                                          |
| RF05       | FRONTEND     |                                                       | Muito alta | Criar uma página de projetos contendo OBRIGATÓRIAMENTE título, resumo, ano de início, status e equipe envolvida.                                                                                                                                                                                                 | 5         | Pendente  |        |      | 26/09/25 | Thiasley,                                                                         |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIAS                     | Muito alta | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | ✅         | DW-005 |      | 26/09/25 | Allan,                                                                            |
| RF07       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PUBLICAÇÕES                  | Muito alta | Criar uma página de publicações contendo artigos, livros, capítulos e etc. com titúlo, revista, autores, ano e link. Além disso a página deverá ter um campo de pesquisa por palavras-chave.                                                                                                                     | 5         | ✅         | DW-007 |      | 26/09/25 | Gianluca,                                                                         |
| RF08       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE CONTATO                      | Alta       | Criar uma página de contato com um formulário com os campos: nome, e-mail. assunto e mensagem. Ao ser confirmado, o formulário deve enviar tudo para o email do agrislab. A página deve conter informações de contato instiucional, links para redes sociais e um mapa para a localização do laboratório no INPE | 3         | Pendente  |        |      | 26/09/25 |                                                                                   |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIA INDIVIDUAL           | Media      | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente  |        |      | 26/09/25 |                                                                                   |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE ENVIO DE NOTICIAS            | Media      | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 8         | 10.00%    | DW-009 |      | 26/09/25 | Allan,                                                                            |
| RNF01      | DESIGN       | TIPOGRAFIA                                            | Urgente    | Definição de uma familia de fontes que serão usadas no projeto todo.                                                                                                                                                                                                                                             | 1         | ✅         | DD014  |      | 17/09/25 | Allan, Gianluca, Guilherme, Lucas Cecon, Lucas Cobra, Nikolas, Victor,            |
| SETUP-01   | INFRA        | Configurar repositório                                | Urgente    | Criar repositório GitHub e estrutura de pastas (HTML, CSS, JS, imagens).                                                                                                                                                                                                                                         | 1         | 60.00%    |        |      | 19/09/25 | Gianluca, Guilherme, Lucas Cecon,                                                 |
| RF01       | FRONTEND     | CRIAÇÂO DE UMA PAGINA HOME - MOBILE                   | Media      | Criar uma página home OBRIGATÓRIAMENTE contendo cards de notícias, projeto, publicações ou outras atualizações, colaboradores, descrições sobre o INPE e o laboratório e previews das demais páginas.                                                                                                            | 5         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF03       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE MEMBROS  - MOBILE            | Media      | Criar uma página referente aos membros do laboratório, descrevendo tambem as respectivas àreas de atuação, nome, foto, função e breve descrição.                                                                                                                                                                 | 3         | ✅         | DW-010 |      | 02/10/25 | Lucas Cecon,                                                                      |
| RF02       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA "SOBRE"  - MOBILE               | Media      | Criar uma página descrevendo com detalhes o laboratório, contendo OBRIGATÓRIAMENTE objetivo, foco, descrição sobre as àreas de atuação e textos explicativos                                                                                                                                                     | 3         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF04       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE VAGAS  - MOBILE              | Media      | Criar uma página de vagas contendo instruções sobre como se candidatar, oportunidades e parcerias estabelecidas pelo laboratório                                                                                                                                                                                 | 3         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF05       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PROJETOS  - MOBILE           | Media      | Criar uma página de projetos contendo OBRIGATÓRIAMENTE título, resumo, ano de início, status e equipe envolvida.                                                                                                                                                                                                 | 5         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIAS  - MOBILE           | Media      | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF07       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE PUBLICAÇÕES  - MOBILE        | Media      | Criar uma página de publicações contendo artigos, livros, capítulos e etc. com titúlo, revista, autores, ano e link. Além disso a página deverá ter um campo de pesquisa por palavras-chave.                                                                                                                     | 5         | Realizado |        |      | 02/10/25 | Gianluca,                                                                         |
| RF08       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE CONTATO  - MOBILE            | Media      | Criar uma página de contato com um formulário com os campos: nome, e-mail. assunto e mensagem. Ao ser confirmado, o formulário deve enviar tudo para o email do agrislab. A página deve conter informações de contato instiucional, links para redes sociais e um mapa para a localização do laboratório no INPE | 3         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE NOTÍCIA INDIVIDUAL  - MOBILE | Media      | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RF06       | FRONTEND     | CRIAÇÃO DE UMA PÁGINA DE ENVIO DE NOTICIAS  - MOBILE  | Media      | Criar uma página de notícias permitindo OBRIGATÓRIAMENTE a publicação de notícias contendo título, data, imagem e texto. As notícias devem ser organizadas cronológicamente                                                                                                                                      | 5         | Pendente  |        |      | 02/10/25 |                                                                                   |
| RNF01      | FRONTEND     | CRIAÇÃO PAGINA BASE  - MOBILE                         | Media      | Criar uma página base com o header e footer que servirá de padrão para todas as páginas seguintes                                                                                                                                                                                                                | 3         | 30.00%    | DW-008 |      | 02/10/25 | Guilherme, Victor,                                                                |
| RF06       | Design       | AUTOMAÇÃO DO FIGMA                                    | Media      | Tornar o FIGMA navegavel e apresentável para a equipe contratante                                                                                                                                                                                                                                                | 1         | ✅         | DD-013 |      | 02/10/25 | Thiasley,                                                                         |
| RNF01      | FRONTEND     | CRIAÇÃO DA PÁGINA DE ATUAÇÃO                          | Media      | Criar página de areas de atuação                                                                                                                                                                                                                                                                                 | 3         | 70.00%    |        |      | 02/10/25 | Guilherme,                                                                        |



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

# APB 1º Semestre DSM

# Desenvolvimento de um website para o laboratório de Sensoriamento Remoto Agrícola do INPE - AgriRS Lab

# Documentação - Sprint 2

<p align="center">
      <img src="../img/nhdevlogo.png" alt="logo" width="200">
      <h2 align="center"> NightHawks</h2>
</p>

<p align="center">
  <a href ="#us">Backlog</a>  |   
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#burndown">Burndown</a>  | 
</p>

> Status da Sprint: Em espera

## 📋 Backlog <a id="us"></a>

| Rank | Prioridade | User Story                                                                                                                                                                                                     | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :------------------: | :----: |
|  7   |    Alta    | Como usuário, eu quero ser alertado caso minha escolha entre LLM1 e LLM2 não esteja coerente com minha avaliação, para que eu possa revisar minha decisão antes de finalizar.                                  |      3       |   2    |         R04          |   ✅   |
|  8   |    Alta    | Como usuário, eu quero que as respostas das LLMs sejam enriquecidas com informações relevantes da base de dados (vetorizada), para que sejam mais precisas                                                     |      5       |   2    |         R07          |   ✅   |
|  15  |   Média    | Como usuário, eu quero poder revisar minha escolha antes de submetê-la, para que eu tenha certeza de que minha decisão está correta.                                                                           |      2       |   2    |         R04          |   ✅   |
|  19  |   Baixa    | Como usuário, eu quero ser informado com mensagens de erro caso ocorra demora excessiva no envio do prompt ou na resposta das LLMs, ou outros erros, para que eu possa entender o problema e tentar novamente. |      2       |   2    |         R03          |   ✅   |
|  21  |   Baixa    | Como usuário, eu quero poder receber mensagens claras sobre o status das avaliações, para ter certeza de que minha avaliação foi registrada corretamente.                                                      |      2       |   2    |         R03          |   ✅   |
|  22  |   Baixa    | Como usuário, eu quero poder voltar para telas anteriores durante o processo de avaliação, para que eu possa corrigir informações antes de enviar a decisão final.                                             |      1       |   2    |       R03/R04        |   ✅   |

## 🏅 DoR - Definition of Ready <a id="dor"></a>

|              Critério              | Descrição                                                                                          |
| :--------------------------------: | -------------------------------------------------------------------------------------------------- |
|        Contrato da API Definido        | A equipa sabe exatamente quais endpoints criar (ex: GET /api/membros, POST /api/membros), quais métodos usar e qual o formato esperado dos dados (JSON).|

|  Modelo de Dados (Schema) Desenhado  | A estrutura da tabela no banco de dados está definida (ex: a tabela membros terá as colunas id, nome, foto_url, funcao, descricao, tipo_membro). |

|  Requisitos Funcionais Claros  | A equipa entende a regra de negócio que o back-end precisa de executar (ex: "Ao listar os membros, eles devem ser ordenados alfabeticamente dentro de cada categoria"). |

|            Dependências do Front-end Mapeadas            | Está claro quais informações o front-end (desenvolvido na Sprint 1) precisará consumir desta API. |


## 🏅 DoD - Definition of Done <a id="dod"></a>

|                 Critério                 | Descrição                                                                                                        |
| :--------------------------------------: | ---------------------------------------------------------------------------------------------------------------- |
|     Código foi Revisto     | Pelo menos um outro membro da equipa revisou o código do back-end. |

| Endpoints Funcionais e Testados | Os endpoints da API foram implementados e testados (seja com testes automáticos ou ferramentas como Postman/Insomnia) para garantir que retornam os dados e os erros corretos. |

|      Banco de Dados Implementado      | A estrutura da tabela foi criada no ambiente de desenvolvimento do banco de dados. |

|       Lógica de Negócio Cumprida       | Todas as regras de negócio associadas à tarefa (ex: ordenação, filtros) foram implementadas. |

|        Documentação da API Criada         | Os novos endpoints foram documentados para que a equipa de front-end saiba como usá-los na próxima fase. |

## 🏅 Sprint Burndown <a id="burndown"></a>

<p align="center">
      <img src="../../../img/Burndown_Sprint2.jpg" alt="Burndown Sprint 2" width="500">
</p>

</div>
# APB 1º Semestre DSM

# Desenvolvimento de um website para o laboratório de Sensoriamento Remoto Agrícola do INPE - AgriRS Lab

# Documentação - Sprint 3

<p align="center">
      <img src="../../img/nhdevlogo.png" alt="logo" width="200">
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
|        Componente de Front-end Finalizado        | A parte visual da funcionalidade (da Sprint 1) está completa e pronta para receber dados reais. |
|  Endpoint da API Finalizado  | O back-end (da Sprint 2) está funcional, testado e a sua documentação está disponível. |
|  Objetivo da Integração Claro  | A equipa sabe exatamente o que precisa de ser conectado e como o resultado final se deve comportar (ex: "Os dados dos membros que vêm do banco de dados devem aparecer na página de equipa"). |
|            Acesso Necessário Garantido            | Se a tarefa for de publicação (deployment), a equipa tem acesso às credenciais do serviço de hospedagem. |


## 🏅 DoD - Definition of Done <a id="dod"></a>

|                 Critério                 | Descrição                                                                                                        |
| :--------------------------------------: | ---------------------------------------------------------------------------------------------------------------- |
|     Funcionalidade Completa de Ponta a Ponta     | O front-end, o back-end e o banco de dados estão a comunicar-se perfeitamente. A funcionalidade trabalha como um todo. |
 Todos os Requisitos do PDF Atendidos | A funcionalidade cumpre todos os seus Requisitos Funcionais (RF) e Não Funcionais (RNF) descritos no documento do projeto. |
|      Testado e Aprovado      | A funcionalidade foi testada por completo pela equipa, não tem bugs críticos, e idealmente, foi validada pelo cliente ou focal point do projeto. |
|       Código Finalizado e Publicado       | O código está na versão final (branch main ou master) e a funcionalidade está publicada no ambiente final (servidor de produção). |

## 🏅 Sprint Burndown <a id="burndown"></a>

<p align="center">
      <img src="../../../img/Burndown_Sprint2.jpg" alt="Burndown Sprint 2" width="500">
</p>

</div>
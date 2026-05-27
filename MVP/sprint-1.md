

# 📌 Sprint 1 - [Análise da Movimentação de Cargas]

## 🎯 Objetivo do MVP  
O propósito deste MVP é fornecer uma ferramenta de Business Intelligence (BI) para a análise do fluxo de cargas especiais e perigosas no Brasil, com foco inicial no estado de São Paulo.
- Qual problema resolve? A falta de padronização e limpeza dos dados brutos do IBAMA, que impede análises imediatas.  
- Qual hipótese será validada? A viabilidade de utilizar Python para automatizar o tratamento de dados públicos e sua integração direta com o Power BI para exibir métricas estaduais.  
- Qual valor será entregue ao usuário final? Acesso a uma base de dados normalizada e visualização clara do fluxo de cargas no estado de São Paulo.
---

## 📝 Descrição da Solução
Desenvolvimento de um dashboard interativo no Power BI, alimentado por uma base de dados processada em Python(Google Colab).  
- Funcionalidades principais incluídas:
   Scripts de limpeza e normalização de dados utilizando Python no Google Colab,
   Dashboard inicial com métricas de movimentação de cargas específicas para o estado de São Paulo.  
- Limitações conhecidas:
   Dados limitados ao recorte geográfico de São Paulo e ausência de funções avançadas como matriz Origem-Destino ou tendências históricas complexas.
- Escopo reduzido:
   Foco total na integridade dos dados e na caracterização do produto logístico regional.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Analista de Dados Governamentais: Necessita que os dados do RAPP (IBAMA) estejam prontos para uso sem erros de formatação.
- **Persona 2:** Gestor Público Regional (SP): Necessita identificar rapidamente disparidades de infraestrutura e fluxo de cargas perigosas dentro do estado de São Paulo.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como um Tomador de Decisões Públicas, quero acessar os dados brutos do IBAMA devidamente limpos e normalizados em Python, para garantir análises confiáveis.         | Alta       | 8 horas   |
| US2 | Como um Tomador de Decisões Públicas, quero visualizar métricas de movimentação de cargas no estado de São Paulo, para identificar necessidades de infraestrutura.         | Alta      | 5 horas   |


## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | ETL em Python (Limpeza/Normalização) e Métricas de SP                      | Concluído|
| 02     | Métricas Nacionais, Filtros de Modais e Tipos de Carga                         | Planejado |
| 03     | Matriz Origem-Destino, Evolução Histórica e Registro RAPP                           | Planejado |

---

## 📊 Critérios de Aceitação
- A base de dados deve ser processada diretamente do portal do IBAMA via Google Colab.  
- O dashboard deve apresentar métricas claras de movimentação (quais cargas e principais modais) para o estado de São Paulo.
- O controle de versão do código Python e dos arquivos do Power BI deve estar registrado no GitHub.

---

## 📈 Métricas de Validação
- Número de usuários que acessaram/testaram o dashboard.
- Feedback qualitativo de gestores e empresas (clareza das informações, usabilidade).
- Indicadores de negócio:
% de adesão ao uso do painel em sala de aula.
Identificação de novos mercados emergentes nos dados.  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Requisitos do Cliente 
- Prints/Protótipos do Dashboard (Power BI). (https://drive.google.com/file/d/1jX4SIoGkHoCGwMp0qMg23IijD-8vGCd2/view?usp=drive_link)
- Repositório GitHub
- Power BI <td align="center"><video src="https://github.com/user-attachments/assets/ae20a002-ffae-4683-8368-9d9d1ab7bea9"></video></td> 
- Limpeza de Dados Phyton <td align="center"><video src="https://github.com/user-attachments/assets/64234f99-a9b7-49ef-9858-ec3ea868e59a"></video></td> 








# 📌 Sprint 2 - [Dashboard de Fluxo de Cargas Especiais e Perigosas]

## 🎯 Objetivo do MVP  
O propósito deste MVP é fornecer uma ferramenta de inteligência de dados voltada ao monitoramento logístico de cargas perigosas e especiais.
- Qual problema resolve? A falta de centralização, padronização e visualização clara dos dados brutos do IBAMA, dificultando a fiscalização e a formulação de políticas públicas de segurança e infraestrutura.  
- Qual hipótese será validada? A hipótese de que a disponibilização de uma interface intuitiva com métricas nacionais, mapeamento de origens/destinos e recortes por modais e municípios melhora a assertividade na tomada de decisões regulatórias e ambientais.  
- Qual valor será entregue ao usuário final? Transparência e agilidade no acesso a dados consolidados de movimentação anual, identificação de modais críticos e mapeamento geográfico das rotas.
---

## 📝 Descrição da Solução
Desenvolvimento de um dashboard interativo no Power BI alimentado por uma base de dados previamente limpa e normalizada em Python.  
- Funcionalidades principais incluídas:
  Painel de controle centralizado (Página Inicial com navegação dinâmica).
  Filtros globais por Ano (2013-2024/2025), Municípios e Empresas.
  Indicadores de quantidade transportada por produto químico/GL e por tipo de armazenagem.
  Análise de evolução histórica (movimentação anual vs. número de operações).
  Mapeamento da Situação Cadastral das empresas e percentual com plano de emergência.
  Distribuição municipal e Matriz Origem-Destino (OD) de fluxos rodoviários/ferroviários/etc.
  Visualização geográfica detalhada através de mapas de rotas (internas de SP e conexões BR-SP).  
- Limitações conhecidas:
  Os dados dependem da periodicidade de atualização e registro das empresas junto ao IBAMA (RAPP).
- Escopo reduzido:
  Foco estrito no fluxo que envolve o estado de São Paulo e o panorama nacional correlato, sem cruzamento com dados financeiros ou faturamento das empresas.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Tomador de Decisões Públicas (ex: Gestores do IBAMA / Secretarias de Logística e Transportes): Necessita identificar disparidades regionais de infraestrutura e gargalos logísticos. Sofre com a dispersão de relatórios manuais e precisa formular políticas de segurança mais assertivas com base em dados confiáveis.
- **Persona 2:** Analista de Fiscalização Ambiental / Regulatório: Necessita monitorar o cumprimento das normas das empresas e o registro adequado (RAPP), além de mapear rotas de maior risco (cargas perigosas) para planejar operações de campo.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US3 | Como um Tomador de Decisões Públicas, quero visualizar métricas de movimentação de cargas em nível nacional, para identificar disparidades regionais e necessidades de infraestrutura.         | Alta       | 8 horas   |
| US4 | Como um Tomador de Decisões Públicas, quero identificar as principais cargas perigosas e especiais movimentadas, para formular políticas de segurança e fiscalização mais assertivas.         | Alta      | 8 horas   |
| US5 | Como um Tomador de Decisões Públicas, quero analisar os principais modais de transporte utilizados para essas cargas, para otimizar a matriz logística e reduzir riscos ambientais.         | Alta      | 6 horas   |
| US6 | Como um Tomador de Decisões Públicas, quero visualizar a Matriz Origem-Destino (OD) das cargas, para compreender o fluxo logístico e o impacto do comércio exterior nos municípios.         | Alta      | 8 horas   |



## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | ETL em Python (Limpeza/Normalização) e Métricas de SP                      | Concluído|
| 02     | Métricas Nacionais, Filtros de Modais e Tipos de Carga, Matriz Origem-Destino                  | Concluído |
| 03     | Evolução Histórica e Registro RAPP                           | Planejado |

---

## 📊 Critérios de Aceitação
- O dashboard deve permitir que o usuário navegue entre as visões ("Transporte e Armazenagem", "Movimentação Anual", "Situação das Empresas", "Situação Municipal", "Movimentação por Modais" e "Mapa de Rotas") a partir de uma tela inicial interativa.
- O sistema deve filtrar instantaneamente todos os gráficos ao selecionar um ano específico no painel lateral.
- Os mapas devem exibir visualmente a espessura ou fluxo das rotas conforme o volume de operações ou gigalitros (GL) transportados.

---

## 📈 Métricas de Validação
- Taxa de cliques na navegação: Verificar se os usuários conseguem alternar entre os menus sem dificuldades (UX).
- Tempo de resposta do relatório: Medir o tempo de renderização dos mapas e gráficos volumosos ao alternar os filtros de anos/municípios.
- Indicadores de negócio:
% de adesão ao uso do painel em sala de aula.

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
- Power BI <td align="center"><video src="https://github.com/user-attachments/assets/5b470f25-ee60-44c5-a024-789f364e7405"></video></td>
- Limpeza de Dados Phyton <td align="center"><video src="https://github.com/user-attachments/assets/64234f99-a9b7-49ef-9858-ec3ea868e59a"></video></td> 











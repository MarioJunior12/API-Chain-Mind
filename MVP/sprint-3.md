# 📌 Sprint 3 - [Dashboard Final de Fluxo de Cargas Especiais e Perigosas]

## 🎯 Objetivo do MVP  
O propósito deste MVP é fornecer uma ferramenta de inteligência de dados voltada ao monitoramento logístico de cargas perigosas e especiais.
- Qual problema resolve? A carência de mecanismos de análise de tendência histórica a longo prazo e a falta de visibilidade imediata das empresas que operam à margem das exigências de planos de emergência ambientais, gerando vulnerabilidade para a fiscalização técnica e ambiental.  
- Qual hipótese será validada? A hipótese de que a inclusão de gráficos de tendência plurianual combinados com o rastreamento individual do perfil de conformidade das empresas permite prever demandas futuras e direcionar ações de fiscalização preventiva de forma mais eficiente. 
- Qual valor será entregue ao usuário final? Um diagnóstico preditivo e acionável que integra regularidade técnica das frotas corporativas, identificação direta dos maiores transportadores logísticos do mercado e projeção histórica de volumes e operações.
---

## 📝 Descrição da Solução
Desenvolvimento de um dashboard interativo no Power BI alimentado por uma base de dados previamente limpa e normalizada em Python.  
- Funcionalidades principais incluídas:
  Painel de tendências históricas cobrindo integralmente o comportamento operacional e o decoupling volumétrico ocorrido na série de 2013 a 2024/2025.
  Gráficos avançados de segmentação corporativa evidenciando o status cadastral (empresas ativas vs. encerradas).
  Painel de risco físico com o percentual de aderência e ausência de Planos de Emergência cadastrados junto à CETESB e à ANTT.
  Ranking detalhado de quantidade de operações dominado pelas maiores corporações do setor.
- Limitações conhecidas:
  Necessidade de alinhamento e auditoria em fontes primárias externas para mitigar erros sistêmicos de input, como as inconsistências de classificação encontradas no modal aéreo.
- Escopo reduzido:
  Conclusão focada estritamente no tripé regulatório de análise histórica, controle modal e governança de conformidade de risco para a esfera de gestão pública.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Tomador de Decisões Públicas (Gestores de Agências e Secretarias): Necessita monitorar a infraestrutura de transporte e entender a evolução e a dependência modal a longo prazo. Busca dados integrados para subsidiar a formulação de políticas públicas de segurança e planejar o reequilíbrio da matriz de transportes.
- **Persona 2:** Analista de Fiscalização Regulatória e Ambiental (ex: Agentes de Controle): Necessita identificar de maneira ágil quais transportadoras possuem maior volume de movimentação e quais operam sem planos de emergência válidos. Sofre com a falta de dados cruzados e busca mitigar passivos regulatórios no mercado.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US7 |  Como um Tomador de Decisões Públicas, quero acompanhar a evolução histórica da movimentação (2013-2025) através de gráficos de tendência, para prever demandas futuras e avaliar o impacto de políticas passadas.         | Alta       | 8 horas   |
| US8 |  Como um Tomador de Decisões Públicas, quero identificar as principais cargas perigosas e especiais movimentadas, para formular políticas de segurança e fiscalização mais assertivas.         | Alta      | 8 horas   |
| US9 | Como um Tomador de Decisões Públicas, quero analisar os principais modais de transporte utilizados para essas cargas, para otimizar a matriz logística e reduzir riscos ambientais.         | Alta      | 6 horas   |



## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Extração, tratamento, limpeza e normalização da base de dados brutos utilizando Python; Estruturação inicial das primeiras métricas de movimentação no Estado de São Paulo.                      | Concluído|
| 02     | Implementação de análises de abrangência nacional, desenvolvimento da matriz Origem-Destino municipal, visualização do painel específico de transporte por modais e geração dos mapas de rotas geográficas interativas.                  | Concluído |
| 03     | Finalização do painel de evolução histórica e tendências, consolidação dos indicadores de regularidade de plano de emergência e perfil corporativo das empresas, e refinamento de usabilidade e responsividade no Power BI.                           | Concluído |

---

## 📊 Critérios de Aceitação
- O sistema deve permitir visualizar o percentual exato de empresas ativas/encerradas e a proporção de conformidade com planos de emergência de risco ambiental.
- O painel de tendências deve plotar de forma clara os pontos históricos de desacompanhamento das curvas operacionais e de gigalitros certificados.
- A interface unificada deve garantir o acesso a qualquer um dos painéis analíticos com apenas um clique a partir do menu da página inicial.

---

## 📈 Métricas de Validação
- Taxa de cliques na navegação: Verificar se os usuários conseguem alternar entre os menus sem dificuldades.
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
- Prints/Protótipos do Dashboard
- Link drive Power Bi (https://drive.google.com/file/d/1riCB6zpeO-aiJbT5ORcKAvQc11yySdmt/view?usp=drive_link)
- Repositório GitHub
- Power BI <td align="center"><video src="https://github.com/user-attachments/assets/7732ce29-ab4a-46af-a827-a6e6492f65bd"></video></td>
- Limpeza de Dados Phyton <td align="center"><video src="https://github.com/user-attachments/assets/64234f99-a9b7-49ef-9858-ec3ea868e59a"></video></td> 















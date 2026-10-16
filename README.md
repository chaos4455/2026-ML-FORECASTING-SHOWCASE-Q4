# 📈 Advanced Time Series Analytics, Demand Forecasting & Decision Intelligence
## 🧠 Modelagem Econométrica, Machine Learning & Inteligência de Estoque de Alta Criticidade

![Time Series](https://img.shields.io/badge/Time_Series-Forecasting_Expertise-6f42c1?style=for-the-badge&logo=python&logoColor=white)
![Decision Intelligence](https://img.shields.io/badge/Decision_Intelligence-Supply_Chain_%26_RevOps-ffd700?style=for-the-badge&logoColor=black)
![MLOps & Benchmark](https://img.shields.io/badge/Benchmark-Blind_Backtesting-181717?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Enterprise Impact](https://img.shields.io/badge/Business_Impact-R%24_1M%2B_Desbloqueado-8a2be2?style=for-the-badge)
![Elias Andrade](https://img.shields.io/badge/Author-Elias_Andrade-000000?style=for-the-badge)

---

## 🎯 Sumário Executivo do Case Real Aplicado

Este repositório documenta a metodologia, o arcabouço matemático e a esteira de engenharia preditiva implementados por **Elias Andrade** na função de **Especialista Sênior em Dados, Supply Chain e Inteligência de Estoque** em uma **Indústria e Distribuidora Multinacional de Grande Porte do setor de Autopeças**.

A operação exigiu a transição completa de um modelo analítico manual para uma arquitetura autônoma orientada a dados (*Decision Intelligence*), integrando a cadeia de suprimentos de ponta a ponta: da previsão estatística da demanda por SKU até o balanceamento de inventário entre **3 filiais**, processos de **importação** e **manufatura própria**.

### 🏆 Indicadores de Negócio e Impacto Operacional Comprovado

| Métrica de Negócio / KPI | Estado Anterior (Manual) | Estado Atingido (Enterprise Data Engine) | Impacto Financeiro / Operacional |
| :--- | :--- | :--- | :--- |
| **Receita Adicional Desbloqueada** | R$ 0,00 (Vendas perdidas não rastreadas) | **> R$ 1.000.000,00 / ano** | Captura de orçamentos não convertidos por ruptura de estoque e reposição cirúrgica. |
| **Disponibilidade do Catálogo Ativo** | Variável com gargalos crônicos | **99,5% de Disponibilidade Operacional** | Sustentada em um portfólio de mais de **1.700 SKUs** de giro contínuo. |
| **Ruptura Absoluta de Itens Críticos** | Descentralizada e sem visibilidade | **Apenas 7 a 20 itens / mês em falta** | Mínimo histórico atingido, contemplando SKUs de cauda longa e dinâmica multi-filial. |
| **Acurácia Preditiva (WAPE)** | Heurísticas empíricas (> 25% de desvio) | **3,16% a 5,15% (SARIMA Validado)** | Redução massiva de excesso de inventário e eliminação de compras de emergência. |
| **Tempo de Diagnóstico em Compras** | Dias de cruzamento em planilhas | **Segundos (Copiloto Chat2SQL)** | Democratização analítica em linguagem natural para compradores e diretores. |
| **Maturidade e Cultura de Decisão** | Apoio em "feeling" comercial | **Operação 100% Data-Driven (< 8 meses)** | Adoção corporativa multidisciplinar estendida para Crédito, Risco e Comercial. |

---

## 🔬 O Framework Científico: A Batalha das Arquiteturas Preditivas

Prever séries temporais no segmento de autopeças e bens industriais envolve sazonalidades acentuadas, choques exógenos de mercado, volatilidade de cauda longa e dependência direta do nível de serviço logístico. Para assegurar máxima aderência entre a previsão estatística e a demanda real de fábrica, foi estruturado um ambiente rigoroso de **Backtesting Cego** (*Out-of-Time Blind Testing*).

### 📐 Metodologia de Validação e Teste Cego (Ano 2025)
- **Base Histórica de Treinamento**: Séries temporais mensais consolidadas de janeiro de 2021 a dezembro de 2024 (48 meses contínuos de ingestão).
- **Janela Cega de Validação (OOT)**: Ano civil completo de 2025, onde os modelos operaram sem acesso aos dados reais correntes, simulando a tomada de decisão antecipada de planejamento fabril e compras.
- **Métricas Oficiais de Auditoria**:
  - **WAPE (*Weighted Absolute Percentage Error*)**: Métrica prioritária de negócio, imune a distorções provocadas por SKUs de volume zero ou cauda longa.
  - **MAE (*Mean Absolute Error*)**: Volume absoluto de unidades ou receita financeira em desvio mensal.

---

### 📊 Tabela Comparativa de Performance dos Modelos Auditados

| Arquitetura Avaliada | Classificação de Performance | WAPE (Ano Cego Demanda) | MAE (Volume Físico) | WAPE (Receita Bruta B2B) | Comportamento Observado no Período de Teste |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **SARIMA (Sazonal Integrado)** | 🥇 **1º Lugar (Vencedor)** | **5,15% a 5,65%** | **26.441 a 28.237 un** | **3,16% (MAE: R$ 578k)** | Capturou perfeitamente os picos sazonais de meio e fim de ano, adaptando-se à tendência linear sem oscilações espúrias. |
| **Regressão Linear / ML Tradicional** | 🥈 **2º Lugar (Alta Aderência)** | **10,06% a 10,86%** | **51.602 a 54.220 un** | **3,39% (MAE: R$ 620k)** | Excelente resposta para projeção agregada de faturamento financeiro; leve atraso na amplitude máxima de picos de unidades físicas. |
| **ARIMA (Não-Sazonal)** | 🥉 **3º Lugar (Degradação)** | **14,87% a 14,94%** | **74.275 a 76.643 un** | **6,64% (MAE: R$ 1,21M)** | Comportou-se como uma média móvel rígida; incapacidade estrutural de antecipar variações sazonais cíclicas de demanda B2B. |
| **MLP (Multi-Layer Perceptron)** | 🚨 **4º Lugar (Colapso / Overfitting)** | **100,00%** | **499.327 un** | **100,00% (MAE: R$ 18,29M)** | Falha crítica de generalização temporal na ausência de horizonte estendido de décadas, projetando dispersão extrema e colapso a zero. |

---

## 🖼️ Painéis Analíticos e Visualizações Técnicas do Ecossistema

As análises abaixo compõem os motores gráficos gerados pelo *Enterprise Data Engine* para guiar os comitês executivos de compras, diretoria comercial e governança de suprimentos.

---

### 1. Auditoria e Decomposição de Churn B2B ao Longo do Tempo
*Visualização analítica que rastreia os motivos reais de cancelamento ou perda de contratos corporativos, segregando responsabilidades entre Logística, Comercial e Mercado.*

![Auditoria de Perda de Clientes B2B](https://img.shields.io/badge/Visualização-Auditoria_de_Churn_B2B-181717?style=flat-square)

- **Causa Raiz 1 (Pressão Comercial / Concorrência por Preço)**: Representa o maior volume absoluto de perda histórica, exigindo políticas de flexibilização de tabela e inteligência de margem.
- **Causa Raiz 2 (Atrito Operacional / Ruptura Logística e SLA de Entrega)**: A componente que foi diretamente mitigada pelo case — ao reduzir o número de itens em falta para menos de 20 por mês, a evasão provocada por desabastecimento foi quase zerada.
- **Causa Raiz 3 (Inatividade / Encerramento do Cliente)**: Ruído inelástico de mercado, mantendo taxa estável entre 15 e 25 contas por mês.

---

### 2. Dinâmica de Carteira: Expansão da Base Ativa e Fluxo Líquido (Inflow vs Outflow)
*Rastreabilidade da saúde de expansão orgânica de ~5.000 para mais de 7.800 clientes B2B ativos entre 2021 e 2026.*

![Dinâmica da Carteira B2B](https://img.shields.io/badge/Visualização-Base_Ativa_e_Fluxo_de_Contas-6f42c1?style=flat-square)

- **Taxa de Crescimento Anual Composta (CAGR)**: Entre 7% e 11% ao ano, sustentada pela fidelização e entrada consistente de contas recentes.
- **Balanço de Fluxo Mensal**: O monitoramento simultâneo do *Inflow* (Novos Clientes Adquiridos) em relação ao *Outflow* (Abandono/Churn) garantiu que o saldo líquido permanecesse positivo em todos os trimestres avaliados, prevenindo a diluição do faturamento por churn oculto.
- **Maturidade das Contas**: Segregação contínua entre Contas Recentes (< 12 meses), Contas em Expansão (12 a 24 meses) e Contas Maduras / Core Enterprise (> 24 meses).

---

### 3. Faturamento Bruto B2B por Canal de Venda e Projeção Financeira
*Evolução temporal da receita bruta mensal saltando de patamares de R$ 10 Milhões para picos superiores a R$ 20 Milhões mensais.*

![Faturamento Bruto por Canal](https://img.shields.io/badge/Visualização-Receita_por_Canal_de_Negócio-ffd700?style=flat-square&logoColor=black)

- **Canal Enterprise (Key Accounts & Contratos Estratégicos)**: Bloco superior mais resiliente e previsível, respondendo por contratos programados de longo prazo.
- **Canal Mid-Market (Corporativo Médio)**: O principal motor de alavancagem de volume, altamente sensível à disponibilidade imediata de estoque nas três filiais.
- **Canal PME / SMB (Transacional e Reposição Rápida)**: Volume pulverizado que assegura liquidez operacional e absorve a distribuição de itens de giro intermediário.

---

### 4. Gestão Granular de Catálogo: Curva ABC Dinâmica (~1.500 SKUs)
*Curva de pareto temporal que define a frequência de ressuprimento, estoque de segurança e parametrização dos pontos de pedido de cada família de itens.*

![Curva ABC Dinâmica](https://img.shields.io/badge/Visualização-Curva_ABC_ao_Longo_do_Tempo-8a2be2?style=flat-square)

- **Classe A (Alta Criticidade / 20% SKUs / 80% Volume)**: Itens de altíssimo giro e volatilidade acentuada (com picos mensais atingindo mais de 650.000 unidades). Recebem parametrização estatística diária e abastecimento prioritário.
- **Classe B (Demanda Média / 30% SKUs / Frequência Regular)**: Comportamento previsível com volume estabilizado entre 80.000 e 150.000 unidades mensais.
- **Classe C (Cauda Longa / 50% SKUs / Baixa Frequência)**: Demanda na faixa de 25.000 a 40.000 unidades agregadas. Aplicação de modelos probabilísticos de Poisson e reposição sob demanda para evitar obsolescência de capital.

---

### 5. Intensidade Transacional: Pedidos Únicos e Sustentação do Ticket Médio
*Auditoria da disciplina comercial cruzando o volume total de pedidos operados frente ao ticket médio corporativo efetivo.*

![Intensidade Transacional](https://img.shields.io/badge/Visualização-Pedidos_vs_Ticket_Médio_Corporativo-181717?style=flat-square)

- **Faixa de Ticket Médio Alvo**: Parametrização rígida para manter o ticket médio corporativo estabilizado entre **R$ 2.500,00 e R$ 2.800,00**, com expansão gradual para **R$ 2.950,00** nos fechamentos de ciclo.
- **Volume de Transações**: Escalabilidade comprovada da infraestrutura de dados suportando o crescimento de 4.000 pedidos/mês para mais de 7.000 pedidos únicos processados mensalmente.
- **Detecção de Desvios de Rentabilidade**: Identificação visual instantânea de momentos em que promoções comerciais elevaram o número de pedidos mas corroeram o ticket médio, permitindo correções ágeis na política de faturamento.

---

### 6. Benchmark Master de Modelos Preditivos no Ano Cego de Teste (2025)
*O teste de fogo dos algoritmos: comparação direta das curvas projetadas contra os dados reais observados mês a mês.*

![Benchmark Master Preditivo](https://img.shields.io/badge/Visualização-Benchmark_Master_SARIMA_vs_Outros-6f42c1?style=flat-square)

- **Validação Prática da Teoria**: Enquanto modelos complexos de redes neurais profundas (MLP) sofreram colapso total por ausência de um horizonte secular de treinamento, o **SARIMA** provou ser a ferramenta industrial mais robusta para previsão de demanda fabril com forte componente sazonal.
- **Aderência aos Picos de Final de Ano**: Apenas os modelos com componente sazonal explícito capturaram a explosão de demanda observada no último trimestre de 2025, garantindo que as ordens de compra emitidas no terceiro trimestre chegassem a tempo nas filiais.

---

## 📚 Matriz Didática e Tomada de Decisão entre Modelos

A escolha do modelo preditivo nunca deve ser orientada pelo modismo tecnológico, mas pela adequação matemática entre o perfil da série temporal e a consequência financeira do erro.

| Família Preditiva | Como Opera a Modelagem | Pontos Fortes Notáveis | Principais Limitações | Cenário Ideal de Aplicação |
| :--- | :--- | :--- | :--- | :--- |
| **ARIMA** | Autocorrelação temporal e diferenciação de séries estacionárias. | Baseline rápido, baixa complexidade computacional, boa interpretação. | Não modela sazonalidade cíclica de forma nativa e rígida. | Séries estáveis com tendência monotônica e sem variações de calendário. |
| **SARIMA** | Expansão do ARIMA com termos sazonais multiplicativos explícitos. | Modela perfeitamente ciclos regulares (anuais, trimestrais, mensais). | Exige identificação precisa da ordem sazonal e estacionariedade. | **Planejamento de Demanda e Compras em Indústrias Sazonais.** |
| **MLP (Deep Learning)** | Redes neurais feedforward aprendendo mapeamento temporal não-linear. | Capacidade teórica de capturar relações multivariadas complexas. | Altíssimo risco de overfitting em séries curtas; requer volume massivo de dados. | Cenários complexos com milhares de variáveis exógenas e big data histórico. |
| **ML Tradicional (XGB / RF / Ridge)** | Algoritmos baseados em árvores e regressões penalizadas com lags. | Excelente com atributos tabulares, promoções, preços e feriados. | Exige intensa engenharia manual de atributos (*lagging, rolling windows*). | Previsão multivariada de vendas sob forte impacto de campanhas e descontos. |
| **Prophet (Meta)** | Modelo aditivo linear/logístico com componentes de decomposição. | Robusto a dados faltantes, outliers e feriados nacionais customizados. | Pode superestimar tendências em mudanças bruscas de regime macroeconômico. | BI operacional, relatórios executivos rápidos e cenários exploratórios. |

---

## 🛠️ Arquitetura de Dados, Pipelines e Copiloto Chat2SQL

Para que a inteligência preditiva chegasse à ponta da operação de compras, foi desenvolvida uma arquitetura unificada de dados e suporte cognitivo à decisão:

### Fluxo Operacional de Dados
1. **Extração & Transformação**: Ingestão automática diária dos bancos transacionais das 3 filiais da distribuidora via scripts Python, consolidando estoques físicos, reservas, mercadorias em trânsito e pedidos pendentes.
2. **Motor Analítico em DuckDB & PyArrow**: Processamento in-memory de milhões de registros de movimentação de materiais e notas fiscais com tempo de execução sub-segundo.
3. **Pipeline Preditivo Automatizado**: Ajuste contínuo dos modelos estatísticos por SKU/Filial, calculando lead times dinâmicos, estoques de segurança probabilísticos e pontos críticos de reposição.
4. **Copiloto Chat2SQL para Compras**:
   - Interface em linguagem natural alimentada por LLMs orquestradas internamente.
   - Permite que o comprador pergunte: *"Quais itens da curva A da filial 2 atingirão o estoque mínimo antes do lead time de importação de 45 dias?"*
   - O copiloto traduz a pergunta em queries SQL analíticas otimizadas, consulta o DuckDB e retorna a resposta formatada com a sugestão do lote econômico de compra já calculado.

---

## 💻 Stack Tecnológica Empregada no Case

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time_Series-4B8BBE?style=for-the-badge)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

- **Linguagem & Ambientes**: Python 3.10+, JupyterLab, Virtual Environments isolados.
- **Manipulação de Séries & Dados**: Pandas, NumPy, Polars, PyArrow, SciPy.
- **Modelagem Estatística & Econométrica**: Statsmodels (ARIMA, SARIMAX, Decomposição STL, Testes Dickey-Fuller / KPSS, Gráficos ACF/PACF).
- **Machine Learning & Redes Neurais**: Scikit-Learn, LightGBM, XGBoost, PyTorch, Keras, TensorFlow, Optuna para Otimização de Hiperparâmetros.
- **Engenharia de Dados & Armazenamento**: DuckDB, PostgreSQL, SQLite, Apache Parquet.
- **Deploy & Aplicações Internas**: FastAPI, Streamlit, Docker, GitOps, interfaces interativas de consumo para compradores e gerentes.

---

## 👨‍💻 Sobre o Especialista

![Elias Andrade Badge](https://img.shields.io/badge/Elias_Andrade-Especialista_em_Dados_%26_Supply_Chain-6f42c1?style=for-the-badge)
![Disponibilidade](https://img.shields.io/badge/Status-Projetos_Estratégicos_%7C_Consultoria-ffd700?style=for-the-badge&logoColor=black)

**Elias Andrade** é Arquiteto de Sistemas, Especialista em Inteligência de Dados, Machine Learning e Supply Chain. Combina mais de 15 anos de vivência em infraestrutura e software com atuação executiva direta na resolução de problemas complexos de inventário, ruptura de vendas, previsão de demanda e governança financeira industrial.

- 📍 **Localização**: Maringá - Paraná, Brasil (Atuação Remota Nacional e Internacional)
- 💼 **LinkedIn**: [linkedin.com/in/itilmgf](https://www.linkedin.com/in/itilmgf/)
- 🌐 **GitHub**: [github.com/chaos4455](https://github.com/chaos4455)
- 🎥 **YouTube Oficial**: [@eliasandradeLLM](https://www.youtube.com/@eliasandradeLLM)
- 📧 **E-mail de Contato**: oeliasandrade@gmail.com
- 📅 **Sessão Estratégica de 30 Minutos**: [Agende via Calendly](https://calendly.com/oeliasandrade/30min)

---
*Este material sintetiza projetos de inteligência operacional de alta fidelidade e metodologias proprietárias de previsão de séries temporais aplicadas à indústria real.*

# 📊 HR Analytics Dashboard - Atlas Labs | Análise de Retenção e Performance de Colaboradores

## 📋 Resumo Executivo

### O Problema do Negócio
A Atlas Labs, uma empresa de tecnologia com 1.470 funcionários, enfrenta uma taxa de atrito de 16,1% (237 colaboradores inativos). A alta rotatividade gera custos elevados com recrutamento, onboarding e perda de conhecimento institucional, impactando diretamente a produtividade e a cultura organizacional.

### A Solução
Desenvolvi um dashboard analítico completo em Power BI para identificar os principais fatores que influenciam o turnover, mapear padrões de atrito por departamento, cargo e perfil demográfico, e fornecer insights acionáveis para a área de RH tomar decisões estratégicas baseadas em dados.

### O Impacto em Números
- **Taxa de atrito identificada:** 16,1% da força de trabalho
- **Departamento mais afetado:** Vendas (Sales) com maior concentração de desligamentos
- **Cargo crítico:** Sales Representative e Recruiter apresentam taxas de atrito superiores a 35%
- **Fator de risco identificado:** Colaboradores que viajam frequentemente apresentam **taxa de atrito 2x maior**
- **Perfil de risco:** Funcionários com menos de 2 anos na empresa têm atrito acima de 30%

---

## 🎯 Descrição do Problema

### Por que este projeto?
A retenção de talentos é um dos maiores desafios das empresas modernas. Altas taxas de turnover impactam negativamente:
- **Custos operacionais:** Recrutamento e treinamento de novos colaboradores
- **Produtividade:** Perda de conhecimento e experiência
- **Cultura organizacional:** Moral da equipe e engajamento

### O que estou tentando resolver?
Este projeto visa **responder perguntas estratégicas** como:
- Quais departamentos e cargos têm maior índice de atrito?
- Existem padrões demográficos associados ao turnover?
- Fatores como frequência de viagem, trabalho overtime e tempo de empresa influenciam a retenção?
- Como a satisfação dos colaboradores evoluiu ao longo do tempo?

### Por que as pessoas devem se importar?
Dados de RH bem analisados permitem:
- **Ações preventivas** para reduzir custos com turnover
- **Programas de retenção** direcionados aos perfis de maior risco
- **Melhoria do clima organizacional** com base em métricas de satisfação
- **Decisões estratégicas** sobre políticas de benefícios, viagens e carga de trabalho

---

## 🔍 Metodologia

### Tipo de Análise
- **Análise Exploratória de Dados (EDA):** Investigação de padrões, outliers e correlações nos dados de RH
- **Análise Descritiva:** Caracterização da força de trabalho por demografia, departamento e cargo
- **Análise de Turnover/Atrito:** Identificação de fatores críticos que impactam a retenção
- **Análise de Performance:** Avaliação de métricas de satisfação e evolução temporal

### Ferramentas e Técnicas Utilizadas
- **Power BI Desktop:** Criação de dashboards interativos e visualizações dinâmicas
- **Power Query:** Transformação, limpeza e preparação dos dados
- **DAX (Data Analysis Expressions):** Criação de medidas calculadas e KPIs customizados
- **Modelagem de Dados:** Estruturação de relacionamentos e otimização do modelo dimensional

### Estrutura do Dashboard
O projeto foi dividido em **4 páginas analíticas**:

1. **Overview** - Visão geral da força de trabalho e tendências de contratação

<img width="1274" height="719" alt="Image" src="https://github.com/user-attachments/assets/815a3eef-8ee6-4337-a62b-88388a01f135" />

2. **Demographics** - Análise demográfica (idade, gênero, estado civil, etnia)

<img width="1269" height="715" alt="Image" src="https://github.com/user-attachments/assets/b72e55b2-8ad7-4be2-bf19-84b3c338eb7c" />

3. **Performance Tracker** - Acompanhamento individual de satisfação e performance

<img width="1281" height="716" alt="Image" src="https://github.com/user-attachments/assets/3242221c-a8b4-4823-9ae2-52257c828e08" />

4. **Attrition** - Análise profunda dos fatores de turnover

<img width="1277" height="718" alt="Image" src="https://github.com/user-attachments/assets/a36148a4-f78f-466b-b42e-603b21fccc9f" />

---

## 🛠️ Habilidades Específicas

### Power Query
- **Extração e Transformação (ETL):** Importação de múltiplas fontes de dados e padronização de formatos
- **Limpeza de Dados:** Tratamento de valores nulos, duplicados e inconsistências
- **Criação de Colunas Condicionais:** Categorização de faixas etárias, níveis salariais e tenure
- **Merge e Append:** Consolidação de tabelas relacionadas

**Medidas DAX criadas:**
- Taxa de atrito geral e segmentada (por cargo, departamento, tenure)
- Contagem de colaboradores ativos vs inativos
- Médias de satisfação (job, relationship, work-life balance)
- Proporções demográficas e distribuições percentuais

### Modelagem de Dados
- **Esquema em Estrela (Star Schema):** Tabela fato (PerformanceRating) relacionada com dimensões (Employees, RatingLevel, SatisfactionLevel, Date)
- **Relacionamentos 1:N:** Configuração de cardinalidade e direção de filtros
- **Tabelas Calendário:** Criação de dimensão temporal para análises de tendência

<img width="815" height="762" alt="Image" src="https://github.com/user-attachments/assets/7c44db60-1afe-4304-883a-ed7588fb76b1" />

### Visualização de Dados
- **KPIs Cards:** Destaque de métricas principais (total de funcionários, taxa de atrito, idade média)
- **Gráficos de Barras e Colunas:** Comparação de atrito por cargo e tenure
- **Gráficos de Linha:** Evolução temporal de satisfação e contratações
- **Treemaps:** Distribuição hierárquica por departamento e cargo
- **Donut Charts:** Proporções demográficas (estado civil, gênero)
- **Design Consistente:** Paleta de cores verde e azul marinho, alinhamento e espaçamento padronizados

---

## 📊 Principais Insights e Resultados

### 1. Perfil Demográfico da Força de Trabalho
- **Distribuição Etária:** Maior concentração de colaboradores na faixa 20-29 anos (>550 funcionários)
- **Diversidade de Gênero:** Aproximadamente 50% feminino e 50% masculino
- **Estado Civil:** 44,2% casados, 34,1% solteiros, 21,6% divorciados
- **Diversidade Étnica:** Predominância de colaboradores brancos, seguidos por afro-americanos e outras etnias

### 2. Estrutura Organizacional
- **Departamento Dominante:** Tecnologia representa mais de 1.000 colaboradores ativos
- **Cargos com Maior Volume:** Software Engineer é a função mais comum
- **Salário Médio por Etnia:** Variação de $107k a $125k, com americanos indianos/nativos do Alasca apresentando média salarial mais alta

### 3. Fatores Críticos de Atrito

#### 📍 **Por Cargo (Maiores Taxas de Atrito)**
- **Sales Representative:** ~38% de atrito
- **Recruiter:** ~35% de atrito
- **Data Scientist:** ~25% de atrito
- **Sales Executive:** ~18% de atrito

#### 📍 **Por Tempo de Empresa (Tenure)**
- **0-1 ano:** ~32% de atrito (período crítico de adaptação)
- **1-2 anos:** ~35% de atrito (maior taxa identificada)
- **3+ anos:** Taxa de atrito reduz progressivamente para <10%

#### 📍 **Por Frequência de Viagem**
- **Frequent Traveller:** ~25% de atrito
- **Some Travel:** ~20% de atrito
- **No Travel:** ~10% de atrito
- **Conclusão:** Colaboradores que viajam frequentemente têm **2,5x mais chance** de deixar a empresa

#### 📍 **Por Overtime**
- **Trabalham Overtime:** ~35% de atrito
- **Não trabalham Overtime:** ~10% de atrito
- **Conclusão:** Colaboradores com carga extra têm **3,5x mais atrito**

### 4. Tendências Temporais
- **Pico de Contratações:** 2012 e 2022 apresentaram os maiores volumes de contratação
- **Evolução do Atrito:** Variação entre 12-28% ao longo dos anos, com picos em 2016 e 2020
- **Padrão Atual:** Tendência de estabilização próxima a 15% nos últimos anos

### 5. Performance e Satisfação (Caso: Estelle Chung)
- **Job Satisfaction:** Declínio de 5 para 3 entre 2020-2022
- **Relationship Satisfaction:** Queda de 5 para 3 no mesmo período
- **Self Rating:** Variação significativa (4 → 3 → 5 → 3)
- **Manager Rating:** Declínio consistente de 4 para 2
- **Work-Life Balance:** Melhora de 2 para 4, indicando ajustes positivos

---

## 💡 Recomendações Estratégicas para o Negócio

### 🎯 **Prioridade Alta - Ação Imediata**

1. **Programa de Retenção para Novos Colaboradores (0-2 anos)**
   - Implementar mentoria estruturada nos primeiros 6 meses
   - Criar marcos de acompanhamento (30-60-90 dias)
   - Oferecer plano de desenvolvimento de carreira claro desde o onboarding

2. **Revisão da Política de Viagens**
   - Reduzir frequência de viagens para cargos críticos
   - Implementar sistema de rotação para viagens frequentes
   - Oferecer compensações adicionais (folgas, bônus) para frequent travellers

3. **Gestão de Overtime**
   - Auditar departamentos com alta incidência de horas extras
   - Considerar contratações adicionais em áreas sobrecarregadas
   - Implementar política de banco de horas e compensação

### 🎯 **Prioridade Média - Curto Prazo**

4. **Foco em Cargos de Alto Atrito**
   - **Sales Representative:** Revisar plano de comissionamento e metas
   - **Recruiter:** Avaliar carga de trabalho e ferramentas disponíveis
   - **Data Scientist:** Criar trilha de especialização e projetos desafiadores

5. **Melhorar Gestão de Performance**
   - Treinar gestores em feedback contínuo (casos como Estelle Chung)
   - Implementar check-ins trimestrais de satisfação
   - Criar planos de ação para colaboradores com ratings em declínio

6. **Pesquisas de Clima Organizacional**
   - Realizar pulse surveys trimestrais
   - Agir rapidamente sobre feedback de insatisfação
   - Comunicar ações tomadas com base no feedback

### 🎯 **Prioridade Baixa - Médio/Longo Prazo**

7. **Diversidade e Inclusão**
   - Expandir programas de diversidade para todas as etnias
   - Garantir equidade salarial entre grupos demográficos
   - Criar comitês de D&I por departamento

8. **Análise Preditiva de Atrito**
   - Desenvolver modelo de machine learning para identificar colaboradores em risco
   - Criar alertas automáticos para gestores
   - Intervir proativamente antes do desligamento

---

## 🚀 Próximos Passos

### Para o Projeto
1. **Integração com Dados em Tempo Real:** Conectar o dashboard a fontes de dados atualizadas automaticamente
2. **Modelo Preditivo de Atrito:** Utilizar Python/R para criar algoritmos de previsão de turnover
3. **Análise de Sentimento:** Incorporar dados de pesquisas qualitativas e NLP para análise de comentários
4. **Benchmark de Mercado:** Comparar métricas da Atlas Labs com índices do setor de tecnologia
5. **Automação de Relatórios:** Criar distribuição automática mensal para liderança

### Para Aprendizado Contínuo
- Aprofundar conhecimentos em **DAX avançado** (time intelligence, complex filters)
- Explorar **Power BI Service** para publicação e colaboração
- Estudar **storytelling com dados** para apresentações executivas
- Praticar **Python para análise de dados de RH** (pandas, scikit-learn)
---

## 🎓 Aprendizados e Reflexões

Este projeto me permitiu:
- Aplicar **pensamento analítico estratégico** em um contexto real de RH
- Compreender a importância de **visualizações claras** para diferentes stakeholders (RH, gestores, C-level)
- Perceber como **pequenos insights** (ex: impacto de viagens) podem gerar **grandes mudanças** nas políticas da empresa
- Desenvolver habilidades de **storytelling com dados**, construindo uma narrativa coerente através das páginas do dashboard
- Reconhecer que **dados quantitativos** devem sempre ser complementados com **contexto qualitativo** para ações efetivas

---

## 📞 Contato

**Seu Nome**  
💼 LinkedIn: [linkedin.com/in/seuperfil]([https://linkedin.com/in/seuperfil](https://www.linkedin.com/in/ruan-gabriel-gomes-da-silva-b4519b20a/))  
🐙 GitHub: [github.com/seuusuario]([https://github.com/seuusuario](https://github.com/NotRuan))

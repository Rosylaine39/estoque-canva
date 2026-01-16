# estoque-canva
Previsão de estoque aws canvas


# 📦 Previsão de Estoque Inteligente na AWS com Amazon SageMaker Canvas

## 📌 Entendendo o Desafio
O desafio consiste em **desenvolver um modelo de Machine Learning para Previsão de Estoque**, utilizando o **Amazon SageMaker Canvas**, uma ferramenta no-code da AWS.  
O objetivo é demonstrar, de forma prática, como aplicar ML para resolver um problema real de negócio: **prever a demanda de produtos e apoiar decisões estratégicas de reposição de estoque**.

Além do modelo, é fundamental **documentar todo o processo em um repositório Git**, evidenciando o raciocínio, as etapas executadas e os insights obtidos.

---

## 🎯 Objetivo do Projeto
- Criar um modelo de ML sem código (no-code)
- Prever a demanda futura de produtos
- Reduzir riscos de excesso ou falta de estoque
- Apoiar a tomada de decisão baseada em dados
- Consolidar conhecimentos em ML aplicado na AWS

---

## 🧠 Tecnologias Utilizadas
- **Amazon SageMaker Canvas**
- **Amazon S3**
- **Machine Learning (Regressão / Previsão)**
- **AWS CloudWatch (logs e monitoramento)**
- **GitHub**

---

## 🚀 Etapas do Desenvolvimento

### 1️⃣ Selecionar ou Criar Seu Dataset
- Naveguei até a pasta `datasets` do repositório.
- Escolhi um conjunto de dados adequado para previsão de estoque, contendo informações como:
  - Histórico de vendas
  - Quantidade em estoque
  - Datas
  - Categoria ou tipo de produto
- Quando necessário, o dataset foi ajustado e enriquecido para melhorar a qualidade dos dados.
- O arquivo final foi **enviado para o Amazon SageMaker Canvas**, utilizando o Amazon S3 como fonte de dados.

📌 *O SageMaker Canvas realiza automaticamente a análise inicial e preparação dos dados.*

---

### 2️⃣ Construir e Treinar Seu Modelo de ML
- No SageMaker Canvas:
  - Importei o dataset selecionado.
  - Defini as **variáveis de entrada (features)**, como vendas anteriores, datas e estoque atual.
  - Configurei a **variável de saída (target)** como a quantidade prevista de estoque ou demanda futura.
- Iniciei o treinamento do modelo utilizando o modo automático (AutoML), onde o Canvas:
  - Seleciona o algoritmo mais adequado
  - Ajusta hiperparâmetros
  - Executa validação do modelo

⏳ O tempo de treinamento variou de acordo com o volume de dados.

---

### 3️⃣ Analisar Seu Modelo de ML
Após o treinamento:
- Analisei as **métricas de desempenho** apresentadas pelo SageMaker Canvas.
- Verifiquei as **principais variáveis que influenciam o modelo**, como histórico de vendas e sazonalidade.
- Quando necessário, realizei novos ajustes:
  - Alteração de variáveis
  - Novo treinamento para melhorar a performance

📊 Essa etapa garantiu maior confiabilidade nas previsões geradas.

---

### ⏱️ 10 Minutinhos Depois...
Com o modelo treinado e validado:
- O SageMaker Canvas disponibilizou rapidamente os resultados
- Foi possível visualizar previsões e análises sem necessidade de código
- O modelo ficou pronto para uso em poucos minutos, reforçando a eficiência do ML no-code

---

### 4️⃣ Previsões e Insights Usando Seu Modelo de ML
- Utilizei o modelo para gerar **previsões específicas de estoque**.
- As previsões foram exportadas para análise.
- Principais insights obtidos:
  - Identificação de tendências de consumo
  - Redução do risco de ruptura de estoque
  - Melhor planejamento de compras e reposições
  - Maior eficiência operacional baseada em dados históricos

---

## 📈 Resultados Obtidos
- O modelo apresentou bom desempenho na previsão de demanda
- Variáveis relacionadas ao histórico de vendas tiveram maior impacto
- A solução pode ser facilmente adaptada para outros contextos e tipos de negócio
- O uso do SageMaker Canvas mostrou-se acessível e eficiente para criação de modelos de ML

---

## 🏁 Conclusão
Este projeto demonstrou como o **Amazon SageMaker Canvas** pode ser utilizado para criar soluções de **Machine Learning no-code**, aplicadas a problemas reais de negócio, como a **Previsão de Estoque Inteligente**.

A experiência reforça a importância do uso de dados na tomada de decisão e amplia as habilidades práticas em:
- Machine Learning aplicado
- AWS
- Análise de dados
- Documentação técnica em repositórios Git

---

## 🔗 Entrega
O repositório com toda a documentação e resultados foi enviado na plataforma da **DIO**, conforme solicitado no desafio.

🚀 **Desafio concluído com sucesso!**

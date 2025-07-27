# Telecom X - Utilizando Machine Learning - Alura Challenge

📡 **Análise Preditiva de Churn em Telecom - Challenge Data Science**

Este projeto realiza uma análise detalhada e constrói modelos de machine learning a partir dos dados da empresa Telecom X. O objetivo é identificar os principais fatores que levam ao cancelamento de serviços (churn) e criar um modelo preditivo para identificar clientes com risco de evasão, gerando insights para estratégias de retenção.

📌 **Objetivos**

  * Analisar o perfil demográfico e contratual dos clientes para entender o churn.
  * Identificar as variáveis mais importantes na previsão de cancelamento.
  * Tratar o desbalanceamento de classes na variável-alvo (`churn`) utilizando a técnica SMOTE.
  * Treinar e avaliar o desempenho de modelos de classificação (Random Forest e Regressão Logística).
  * Propor recomendações estratégicas e baseadas em dados para reduzir a taxa de churn.

🧪 **Tecnologias Utilizadas**

  * Python
  * Pandas e NumPy para manipulação e análise de dados
  * Matplotlib e Seaborn para visualizações de dados
  * Scikit-learn para pré-processamento, modelagem e avaliação
  * Imbalanced-learn para balanceamento de classes (SMOTE)
  * Requests para extração de dados
  * Jupyter Notebook como ambiente de desenvolvimento
  * Markdown para documentação e relatórios

📈 **Resultados Principais**

  * **Contrato Mês a Mês e Baixo Tenure:** Confirmados pela análise de importância das features como os principais indicadores de churn.
  * **Cheque Eletrônico e Valor Mensal Elevado:** Também se mostraram fatores de grande influência na decisão de cancelamento.
  * **Desempenho do Modelo Preditivo:** O modelo de **Regressão Logística** apresentou a melhor performance para o objetivo de negócio, alcançando um **recall de 78%** na identificação de clientes que cancelaram, superando o Random Forest neste critério crucial.

🔎 **Para detalhes completos, consulte o [Relatório de Análise de Evasão]**

📤 **Conclusão**

A análise e a modelagem preditiva identificaram um perfil claro do cliente com alto risco de churn: cliente novo, com contrato mensal, valor de conta elevado e que utiliza cheque eletrônico como forma de pagamento. A recomendação principal é focar os esforços de retenção nestes clientes, utilizando o modelo preditivo para identificá-los proativamente e oferecer incentivos para a migração para contratos de longo prazo.

📬 **Contato**

Para dúvidas ou sugestões, entre em contato:

  * **Nome:** [Gabrielly Gomes]
  * **Email:** [gabrielly.gomes@ufpi.edu.br]

📌 *Projeto desenvolvido com fins analíticos e educacionais.*

📊 Análise de Evasão de Clientes (Churn) – TelecomX



🚀 Descrição do Projeto

Este projeto tem como objetivo analisar a evasão de clientes (churn) na empresa TelecomX, utilizando técnicas de análise exploratória de dados (EDA). A evasão de clientes é um dos maiores desafios do setor de telecomunicações, e entender seus fatores é essencial para desenvolver estratégias de retenção.

🧠 Objetivo

📌 Identificar os principais fatores que levam os clientes a cancelarem seus contratos.


📌 Gerar insights que ajudem a TelecomX a reduzir a taxa de churn.


📌 Oferecer recomendações estratégicas baseadas nos dados.



🗂️ Etapas do Projeto

1. 🔍 Introdução
 
O problema de Churn (evasão) refere-se aos clientes que deixam de utilizar os serviços de uma empresa. Compreender esse fenômeno permite criar estratégias para reter clientes, aumentando a rentabilidade e a sustentabilidade do negócio.

🧹 Limpeza e Tratamento dos Dados
 
 Importação do dataset JSON disponibilizado pela Alura.


 Conversão dos dados para DataFrame.


 Verificação e tratamento de valores ausentes.


 Correção de tipos de dados (categóricos e numéricos).


Renomeação de colunas para melhorar a leitura e padronização.


 Tratamento de duplicatas e inconsistências.



2. 📊 Análise Exploratória de Dados (EDA)
   
🔸 Proporção de Churn

Insight: A taxa de churn é aproximadamente 26,5%, um valor alto para o setor.

![image](https://github.com/user-attachments/assets/8672a619-2191-4023-ae59-9ed4ab54397d)



🔸 Churn por Gênero

Insight: O gênero não influencia significativamente na taxa de churn.

![image](https://github.com/user-attachments/assets/c06149ba-2603-4605-95c0-ade4d2f20776)



🔸 Churn por Tipo de Contrato

Insight: Clientes com contratos mensais apresentam uma taxa de churn muito maior.

![image](https://github.com/user-attachments/assets/26acf423-cbca-4fc4-a6ce-55848680a803)



🔸 Churn por Serviços Contratados

Insight:


Clientes sem serviço de internet quase não apresentam churn.


Quem contrata Backup ou Suporte Técnico tem maior propensão a cancelar, o que indica possível insatisfação com esses serviços.


![image](https://github.com/user-attachments/assets/c6f80e19-c016-42b4-9ee4-8716c9437c1b)



🔸 Churn por Método de Pagamento

Insight:


Quem utiliza pagamentos automáticos tem menor taxa de churn.


Clientes que usam boleto ou cheque eletrônico estão mais propensos a cancelar.


![image](https://github.com/user-attachments/assets/fed4d9dc-9a72-427d-b4d5-a87594b671bc)



3. 🔸 Análise de Mensalidade (Monthly Charges)
 
Insight: Mensalidades mais altas estão associadas a maior churn, especialmente em contratos mensais.

Tempo de contrato (tenure) possui correlação negativa — quanto maior o tempo, menor a chance de cancelamento.



4. 🏁 Conclusões e Insights

🏷️ Tipo de contrato é o maior fator preditivo de churn — contratos mensais têm alto risco.


💸 Mensalidades altas, sem entrega de valor percebido, aumentam o churn.


💳 Métodos de pagamento automáticos ajudam na retenção de clientes.


🛠️ Serviços adicionais (como backup e suporte) estão associados a churn — indicando que precisam ser avaliados em termos de entrega de valor.


⏳ Clientes recentes estão mais propensos ao cancelamento — evidenciando a importância do onboarding e acompanhamento no início da jornada.



5. 💡 Recomendações

Incentivar contratos longos, oferecendo descontos ou bônus para quem migra do plano mensal para anual/bienal.


Revisar preços e pacotes, principalmente para clientes com mensalidades elevadas.


Melhorar serviços adicionais como backup e suporte, ajustando sua entrega para aumentar a satisfação.


Promover pagamentos automáticos, oferecendo incentivos para quem adotar débito automático ou cartão recorrente.


Implementar programas de Customer Success, focando no acompanhamento dos clientes nos primeiros meses (fase crítica de churn).


6. 🛠️ Tecnologias Utilizadas

Python

Pandas

Matplotlib

Seaborn

Google Colab

Git e GitHub





7. 🤝 Contato

Feito com 💙 por Aline de Jesus Santos



# Projeto - Análise de Churn da empresa TelecomX

## Tecnologia

Os softwares utilizados neste projeto foram:

* Jupyter Anaconda
* Python


## Serviço usado:

* Github


## Bibliotecas Python

* Pandas
* matplotlib
* seaborn

## Descrição do Projeto </h1>
Este projeto consiste em uma análise de dados de churn para uma empresa de telefonia e internet. O objetivo foi identificar os principais fatores que levam os clientes ao cancelamento de serviços e fornecer insights acionáveis para estratégias de retenção de clientes. Foram realizadas etapas de limpeza de dados, análise exploratória e identificação de padrões cruciais de churn relacionados a métodos de pagamento, tipo de contrato e perfil do cliente (idosos vs. não-idosos).


### 1 - Churn por Faixa Etária: Uma Análise Comparativa (Idosos vs Não-Idosos)
A análise do perfil etário dos clientes revelou uma diferença significativa nas taxas de cancelamento. Clientes idosos apresentaram uma taxa de churn de 41.68%, que é notavelmente maior em comparação com os não-idosos, que registraram 23.61%.
Essa disparidade pode não indicar necessariamente insatisfação com a empresa, mas sim estar relacionada a fatores como idade avançada, falecimento, mudança de rotina ou menor familiaridade e uso de serviços digitais. Para uma retenção eficaz desse segmento, a implementação de estratégias específicas é crucial, incluindo a oferta de planos simplificados e um atendimento ao cliente mais personalizado e acessível.

![Image](https://github.com/user-attachments/assets/4068c5d2-0acd-45a9-bc71-19efd006b846)


### 2 - Análise do Churn por Método de Pagamento
Os Electronic check representam a principal causa de cancelamento, com uma taxa de 45.29% e o maior volume de clientes que cancelaram (1071). Em contraste, os métodos Credit card (automatic) e Bank transfer (automatic) demonstram maior retenção, registrando as menores porcentagens que cancelaram (15.24% e 16.71% respectivamente). Os Mailed check apresentam uma taxa intermediária de cancelamento, com 19.11%.
Para melhorar, incentive a migração para métodos de pagamento automáticos, como Credit card (automatic) e Bank transfer (automatic), que comprovadamente resultam em maior lealdade do cliente.

![Image](https://github.com/user-attachments/assets/53f75ce0-5064-45c7-b021-9c7be84abcb3)


### 3 - Impacto do Método de Pagamento no Churn
A análise dos métodos de pagamento revelou diferenças significativas nas taxas de cancelamento (churn) entre os clientes. Observou-se que o método "Electronic check" apresenta a maior taxa de cancelamento, indicando um possível perfil de cliente menos fidelizado ou mais sensível a questões de serviço ou preço. Isso sugere que esse grupo pode demandar ações específicas de retenção, como ofertas personalizadas ou melhorias no atendimento.
Por outro lado, os clientes que utilizam pagamentos automáticos, como "Credit card (automatic)" e "Bank transfer (automatic)", demonstram menor propensão ao cancelamento. Isso pode refletir um maior engajamento, confiança na empresa e planejamento financeiro. Incentivar esses métodos de pagamento pode ser uma estratégia eficaz para reduzir o churn.
O método "Mailed check" apresentou taxas intermediárias, possivelmente associado a um público mais tradicional. Embora não seja o grupo mais propenso ao churn, ainda pode se beneficiar de ações informativas sobre as vantagens dos pagamentos automáticos.
Em resumo, o tipo de pagamento utilizado pelo cliente pode ser um indicativo importante do seu nível de fidelização, sendo uma variável estratégica para programas de retenção e personalização de ofertas.

![Image](https://github.com/user-attachments/assets/9a7fdd1b-b153-4129-a242-51b24e6329c8)

## Autor

* **Matheus Bonfim do Prado**: @bonfimdoprado (https://github.com/bonfimdoprado)

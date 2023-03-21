
# Conceitos e definições

Abordaremos tambem as definições de Random Forest e Bagging bem como as direnças entre ambos.

# Ilustração de problema real

Desenvolveremos um algorítmo com base na problemática de previsão de temperatura para o próximo dia baseado em modelagem de dados via Random Forest - Bagging.

# Previsao-do-tempo-Seattle
Previsão de temperatura em Seattle-Wa baseada em modelagem de dados em Random Florest - Python

O problema que abordaremos é prever a temperatura máxima para amanhã na cidade de Seattle WA. Vamos agir como se não tivessemos acesso a nenhuma previsão do tempo. O que temos acesso é um ano de temperaturas máximas históricas, as temperaturas dos dois dias anteriores e uma estimativa de um amigo que sempre afirma saber tudo sobre clima. Este é um problema de aprendizado de máquina de regressão supervisionado. É supervisionado porque temos as características e os alvos de temperatura que queremos prever. Durante o treinamento, damos a Random Florest os recursos e os destinos e ela deve aprender como mapear os dados para uma previsão. Além disso, esta é uma tarefa de regressão porque o valor do destino é continuo ( ao contrário de classes discretas na classificação). Isso é praticamente todo o histórico que precisamos


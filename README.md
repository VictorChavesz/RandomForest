# RandomForest
 
Modelo de machine learning para detectar transações fraudulentas em cartões de crédito.

Colunas: <br>
Time: Tempo em segundos desde a primeira transação registrada. <br>
V1, V2, ..., V28: Componentes principais extraídos via PCA (devido à privacidade dos dados originais). <br>
Amount: Valor da transação em dólares. <br>
Class: Variável alvo (0 = transação normal, 1 = fraude). <br>

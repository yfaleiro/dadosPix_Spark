# Detectando fraudes utilizando PySpark

O intuito desse notebook é explorar uma base fictícia que contém dados de transações via PIX de um único cliente de uma conta específica, responder alguns questionamentos e criar um modelo de detecção de transação fraudulenta.

Após a criação de um modelo de identificação de transações fraudulentas e análise exploratória dos dados, chegamos as seguintes conclusões:

1.A categoria com o maior número de transferências foi a de "Transferência Bancária";  
2.O banco mais utilizado foi o banco XP, mas com uma margem pequena em relação aos outros bancos;  
3.É possível supor que esse cliente usa essa conta pessoa física para fazer movimentações de natureza PJ, devido ao número e valor mensal das transações realizadas;  
4.Apenas pela análise dos dados, foi possível identificar que todas as transações fraudulentas tiveram valores maiores que R$ 19.999,00; o que é maior que qualquer transação não fraudulenta realizada pelo cliente;  
5.Uma sugestão de ação para reduzir o número de tentativas de transações fradulentas seria diminuir o valor máximo de transferência em PIX;   

OBS: Devido a natureza fictícia da base, construída para esse tipo de exercício, o modelo desempenhou de forma quase perfeita, provavelmente pela distribuição dos dados, o que está bem evidenciado no ponto 4 acima, onde o valor é um indicador muito forte de fraude.

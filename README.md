A classe InteractionAnalyzerPorChamada é uma classe que possui métodos para analisar e extrair indicadores a partir de um conjunto de dados que contém informações de interações em chamadas. Ela foi criada para facilitar a análise desses dados e permitir a obtenção de insights relevantes a partir desses indicadores.

O método __init__ é o construtor da classe e recebe um objeto df que representa o conjunto de dados a ser analisado.

Os métodos dessa classe utilizam operações de agregação do pandas para calcular indicadores, tais como:

duracao_media_por_chamada: calcula a duração média das interações por chamada;
media_de_palavras_por_chamada: calcula a média de palavras por interação por chamada;
quantidade_de_interacoes_resolvidas: calcula a quantidade de interações resolvidas por chamada;
quantidade_de_interacoes_nao_resolvidas: calcula a quantidade de interações não resolvidas por chamada;
percentual_de_interacoes_resolvidas_por_chamada: calcula o percentual de interações resolvidas por chamada;
inicio_interacao_por_chamada: retorna o horário de início da primeira interação de cada chamada;
fim_interacao_por_chamada: retorna o horário de término da última interação de cada chamada;
duracao_total_por_chamada: calcula a duração total das interações por chamada;
quantidade_total_de_palavras_por_chamada: calcula a quantidade total de palavras por chamada;
quantidade_de_interlocutores_por_chamada: calcula a quantidade de interlocutores por chamada.
Esses métodos retornam os indicadores calculados em forma de objetos do tipo DataFrame, contendo os valores calculados para cada chamada. Com esses indicadores, é possível realizar análises mais detalhadas sobre as interações em chamadas e obter insights importantes para melhorar a experiência dos clientes e a eficiência dos atendimentos.

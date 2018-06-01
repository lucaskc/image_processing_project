# Esteganografia no domínio das frequências


A ideia geral do projeto é usar técnicas aprendidas ao longo do semestre para fazer um trabalho na área de esteganografia. Basicamente a ideia é passar a imagem do Domínio da Imagem para o Domínio das Frequências, e assim trabalhar nas frequências mais altas para poder esconder uma mensagem. A ideia surgiu ao lembrarmos do funcionamento da compressão feita no formato JPEG, que usa a transformada de Cossenos e elimina de forma inteligente os últimos coeficientes, que usualmente são mais próximos ao zero. No caso, ao invés de apagar esses últimos, trabalharíamos para codificar uma mensagem.

Modificando as últimas frequências, há uma alteração da imagem, ficando ruidosa. Será investigado alguns filtros, como filtro adaptativo da média, mediana e filtro convencional Gaussiano. Além de utilizar esses filtros, será aferido o desempenho de cada um para efeito de comparação. A comparação será feita através do cálculo do RMSE da imagem original, filtrada e após processamento (esteganografia).

# Estudo.GridSearchCV.RandomSearchCV

#### Grid SearchCV:

- Técnica de otimização de hiperparâmetros em Machine Learning.
- Realiza uma busca exaustiva em um espaço pré-definido de hiperparâmetros.
- Cria uma grade (grid) com todas as combinações possíveis de hiperparâmetros especificados.
- Treina e avalia o modelo em cada combinação usando validação cruzada.
- Útil para pequenos espaços de busca e quando os hiperparâmetros têm uma influência clara no desempenho do modelo.
- Pode ser computacionalmente intensivo para espaços de busca grandes.

#### Random SearchCV:

- Técnica de otimização de hiperparâmetros em Machine Learning.
- Realiza uma busca aleatória em um espaço pré-definido de hiperparâmetros.
- Seleciona aleatoriamente combinações de hiperparâmetros para treinar e avaliar o modelo usando validação cruzada.
- Eficiente quando os hiperparâmetros não têm uma relação linear clara com o desempenho do modelo.
- Pode superar o Grid SearchCV quando o espaço de busca é grande ou quando recursos computacionais são limitados.
- Menos propenso a ficar preso em mínimos locais em comparação com Grid SearchCV.

#### Conclusão:

Ambos Grid SearchCV e Random SearchCV são técnicas amplamente utilizadas para encontrar a combinação ideal de hiperparâmetros que maximizem o desempenho do modelo em um conjunto de dados específico. A escolha entre eles depende do espaço de busca de hiperparâmetros e dos recursos disponíveis para a otimização.

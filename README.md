# Trabalho Final IA: Otimizando Rotas

Neste trabalho desenvolvemos agentes inteligentes para otimizar o problema de otimização de rotas de viagem, com embasamento teórico nas aulas da disciplina de Inteligência Artificial. Objetivamos implementar modelos de IA em diferentes soluções para o problema proposto.

## Como executar

Basicamente necessita ter uma conta [Google] (https://accounts.google.com) e acessar a página do [Google Colaboratory](https://colab.research.google.com/). Todas as bibliotecas necessárias podem ser apenas declaradas de acordo com o código descrito no projeto e para execução das células no ambiente tem-se o seguinte [vídeo](https://www.youtube.com/watch?v=inN8seMm7UI&ab_channel=TensorFlow).

## Bibliotecas usadas

### Algoritmo Genético

- random;

### A*

- heapq;

### Árvore de Decisão

- scikit-learn;
- random;

### BFS

- collections;

## Adaptação de configurações

Modifique essas configurações iniciais para uso em problemas mais específicos de sua necessidade.
```
# Definir as cidades
cidades = ['A', 'B', 'C', 'D', 'E', 'F']

# Definir as distâncias entre as cidades
distancias = {
    'A': {'B': 10, 'C': 15, 'D': 20, 'E': 25, 'F': 30},
    'B': {'A': 10, 'C': 5, 'D': 40, 'E': 45, 'F': 50},
    'C': {'A': 15, 'B': 5, 'D': 55, 'E': 60, 'F': 65},
    'D': {'A': 20, 'B': 40, 'C': 55, 'E': 10, 'F': 15},
    'E': {'A': 25, 'B': 45, 'C': 60, 'D': 10, 'F': 5},
    'F': {'A': 30, 'B': 50, 'C': 65, 'D': 15, 'E': 5}
}
```

# comparacao-bubble-selection-igorviana
Atividade avaliativa 1 , tabela comparativa , Igor Viana , segue o código e o readme com a análise


# Comparação Bubble Sort vs Selection Sort

Atividade prática para comparar o desempenho dos algoritmos de ordenação.

# Resultados Obtidos

| Algoritmo      | Tamanho | Tempo (ms) | Comparações | Movimentações |
|----------------|---------|------------|-------------|---------------|
| Bubble Sort    | 100     | 0.00       | 4950        | 14850         |
| Selection Sort | 100     | 0.00       | 4950        | 150           |
| Bubble Sort    | 1000    | 1.00       | 499500      | 1498500       |
| Selection Sort | 1000    | 1.00       | 499500      | 1500          |
| Bubble Sort    | 10000   | 126.00     | 49995000    | 149985000     |
| Selection Sort | 10000   | 59.00      | 49995000    | 15000         |

# Conclusão

O algoritmo **Selection Sort** apresentou melhor desempenho.

Embora ambos tenham o mesmo número de comparações (complexidade O(n²)), o Selection Sort realiza drasticamente menos movimentações na memória (trocas) do que o Bubble Sort. Enquanto o Bubble Sort realiza trocas constantes a cada inversão encontrada, o Selection Sort realiza apenas uma troca por ciclo de ordenação.

<img width="1105" height="590" alt="image" src="https://github.com/user-attachments/assets/ea96abe5-cb6b-449f-855e-a0a28b526a46" />

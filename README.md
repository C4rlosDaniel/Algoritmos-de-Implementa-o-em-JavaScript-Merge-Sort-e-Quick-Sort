Merge Sort and Quick Sort

Este repositório contém implementações educacionais dos algoritmos Merge Sort e Quick Sort em Python.
O objetivo é demonstrar, de forma prática e clara, como funcionam dois dos métodos de ordenação mais importantes da Ciência da Computação.

Ambos os algoritmos utilizam a técnica de divisão e conquista e são amplamente empregados em cenários onde eficiência e desempenho são essenciais.

📁 Estrutura do Projeto
algoritmos-ordenacao/
│
├── src/
│   ├── mergesort.py
│   ├── quicksort.py
│   └── main.py
│
└── README.md

🧠 Como funciona
Merge Sort

Divide o array em partes menores, ordena cada parte e depois combina os resultados.
Características principais:

Estável

Complexidade garantida O(n log n)

Requer memória auxiliar

Quick Sort

Seleciona um pivô, particiona o array em elementos menores e maiores e ordena recursivamente.
Características principais:

Excelente desempenho médio: O(n log n)

In-place

Simples de implementar

▶️ Como executar o projeto
1. Clone o repositório
git clone https://github.com/SEU-USUARIO/SEU-REPO.git

2. Execute o arquivo principal
python src/main.py


Se quiser rodar os algoritmos individualmente:

python src/mergesort.py
python src/quicksort.py

📌 Código Fonte (exemplo de uso)
Merge Sort
array = [38, 27, 43, 3, 9, 82, 10]
resultado = merge_sort(array)
print(resultado)

Quick Sort
array = [38, 27, 43, 3, 9, 82, 10]
resultado = quick_sort(array)
print(resultado)

🛡️ Uso Educacional

Este projeto tem finalidade apenas didática, sendo apropriado para:

Aulas e estudos de algoritmos

Comparação entre métodos de ordenação

Preparação para entrevistas técnicas

Demonstrações acadêmicas

📄 Licença

MIT License — Livre para estudos, modificações e uso educacional.

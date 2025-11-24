# Merge Sort e Quick Sort Demo

Este repositório contém um exemplo **educacional** dos algoritmos de ordenação **Merge Sort** e **Quick Sort** implementados em Python.  
O objetivo é demonstrar de forma clara e prática o funcionamento de dois dos algoritmos mais importantes da Ciência da Computação.

⚠️ **AVISO IMPORTANTE**  
Este projeto é **exclusivamente para fins educacionais**. O uso dos algoritmos é seguro, porém este repositório não deve ser interpretado como ferramenta profissional de benchmark ou otimização avançada.

---

## 📁 Estrutura do Projeto

```
algoritmos-ordenacao/
│
├── src/
│   ├── mergesort.py
│   ├── quicksort.py
│   └── main.py
│
└── README.md
```

---

## 🧠 Como funciona

### **Merge Sort**
O algoritmo divide o array em partes menores, ordena cada uma delas e combina os resultados.

**Características principais:**
- Estável  
- Complexidade garantida: **O(n log n)**  
- Requer memória auxiliar  

---

### **Quick Sort**
Escolhe um pivô, particiona o array e ordena recursivamente os elementos.

**Características principais:**
- Excelente desempenho médio: **O(n log n)**  
- In-place  
- Simples de implementar  

---

## ▶️ Como executar o projeto

### 1. Clone o repositório
```bash
git clone https://github.com/SEU-USUARIO/SEU-REPO.git
```

### 2. Execute o arquivo principal
```bash
python src/main.py
```

### Para executar individualmente:
```bash
python src/mergesort.py
python src/quicksort.py
```

---

## 📌 Código Fonte (exemplo de uso)

### Merge Sort
```python
array = [38, 27, 43, 3, 9, 82, 10]
resultado = merge_sort(array)
print(resultado)
```

### Quick Sort
```python
array = [38, 27, 43, 3, 9, 82, 10]
resultado = quick_sort(array)
print(resultado)
```

---

## 🛡️ Uso Educacional

Este projeto destina-se apenas a fins de estudo, como:

- Aulas e demonstrações de algoritmos  
- Comparação entre métodos de ordenação  
- Preparação para entrevistas técnicas  
- Estudos acadêmicos e laboratoriais  

---

## 📄 Licença

Distribuído sob a **MIT License** — livre para uso, modificação e fins educacionais.

## Modelagem com Lógica Fuzzy, Hard Fuzzy e C-Means

A Lógica Fuzzy e suas variantes, como o Hard Fuzzy e o algoritmo de clusterização Fuzzy C-Means, são técnicas amplamente aplicadas quando se deseja representar incertezas, tomar decisões com informações imprecisas ou identificar agrupamentos em dados sem necessidade de rotulagem explícita. Essas abordagens são especialmente úteis em sistemas de controle, classificação e clusterização de padrões complexos.

### Por que usar Fuzzy, Hard Fuzzy e C-Means?

* **Fuzzy**: modela a incerteza linguística; ideal para sistemas de decisão baseados em regras.
* **Hard Fuzzy**: combina regras crisp com variáveis fuzzy, mantendo parte da flexibilidade.
* **Fuzzy C-Means**: identifica grupos em dados, permitindo que um dado pertença parcialmente a múltiplos clusters, o que melhora a interpretação de padrões sobrepostos.

### Funcionamento Intuitivo

Imagine regular a potência de um aspirador de pó: com Fuzzy, pode-se definir níveis linguísticos como “baixa”, “média” ou “alta” de forma contínua, ajustando a potência suavemente conforme a sujeira. No caso de gorjetas em um restaurante, a decisão de quanto pagar pode depender de variáveis linguísticas como “qualidade do serviço” e “qualidade da comida”. Já o Fuzzy C-Means atribui graus de pertencimento de clientes a perfis de consumo, facilitando estratégias de segmentação.

---

### 📂 Estrutura dos Notebooks

#### 1️⃣ Fuzzy\_Aspirador\_de\_Pó\_Orlando.ipynb

📌 **Tarefa**: Controlar a potência de um aspirador com base na quantidade de sujeira e tipo de piso
📚 **Dataset**: Valores sintéticos de sujeira e piso
🔍 **Destaques**:

* Criação de funções de pertinência para entrada e saída
* Conjunto de regras linguísticas IF-THEN
* Sistema de inferência Mamdani para decisão final
* Gráficos de superfícies e membership functions

#### 2️⃣ Fuzzy\_Gorjetas\_Orlando.ipynb

📌 **Tarefa**: Calcular gorjetas ideais com base em serviço e comida
📚 **Dataset**: Avaliações de serviço e comida (exemplo didático)
🔍 **Destaques**:

* Funções de pertinência gaussianas e triangulares
* Regras linguísticas que simulam raciocínio humano
* Visualização de superfícies de decisão
* Demonstração clara da defuzzificação

#### 3️⃣ Fuzzy\_C\_Means\_Orlando.ipynb

📌 **Tarefa**: Realizar clusterização fuzzy em dados não rotulados
📚 **Dataset**: Conjunto de pontos em 2D (para visualização)
🔍 **Destaques**:

* Aplicação do algoritmo Fuzzy C-Means
* Atribuição de graus de pertinência de cada ponto a múltiplos clusters
* Visualização dos centros fuzzy e das fronteiras de cluster
* Comparação com K-Means tradicional para evidenciar vantagens

---

### 📈 Métricas e Avaliação

As modelagens fuzzy e de clusterização foram avaliadas principalmente de forma interpretativa e visual, com:

* Gráficos de membership e superfícies 3D
* Mapas de clusters com pesos de pertinência
* Análise qualitativa da coerência entre variáveis de entrada e saída

---

### ⚙️ Técnicas Utilizadas

* Sistema de inferência Mamdani
* Funções de pertinência triangulares, gaussianas e trapezoidais
* Defuzzificação por centroide
* Algoritmo de otimização Fuzzy C-Means para clusterização suave

---

**Resumo:**
A combinação de Lógica Fuzzy, Hard Fuzzy e Fuzzy C-Means neste trabalho demonstra o potencial dessas abordagens para resolver problemas de controle, decisão e agrupamento em ambientes onde dados imprecisos ou parcialmente conhecidos são a regra. Esses notebooks exemplificam como regras linguísticas, funções de pertinência e algoritmos de clusterização podem ser integrados em soluções inteligentes e interpretáveis.

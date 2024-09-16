# Previsão de Aceitação de Campanha de Marketing

### Descrição

Este projeto tem como objetivo prever se um cliente aceitará uma campanha de marketing com base em dados históricos de clientes, como compras anteriores, participação em campanhas anteriores e características demográficas. O modelo utilizado para realizar essas previsões é o **Random Forest Classifier**, implementado com a biblioteca `scikit-learn`.

### Funcionalidades

- Prever a aceitação de campanhas de marketing.
- Analisar a importância das features no processo de decisão.
- Utilizar gráficos e visualizações para entender a influência de cada variável no modelo.

---

### Tabela de Conteúdos

- [Descrição](#descrição)
- [Instalação](#instalação)
- [Como Utilizar](#como-utilizar)
- [Base de Dados](#base-de-dados)
- [Modelo de IA](#modelo-de-ia)
- [Resultados](#resultados)

---

### Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

---

### Como Utilizar

Após a instalação das dependências, você pode executar o projeto localmente. 

1. **Treinamento do Modelo**:
    - O código treina um modelo Random Forest com a base de dados de clientes e campanhas de marketing. 
    - Execute o script `main.py` ou o arquivo Jupyter Notebook com o código para treinar e testar o modelo:
      ```bash
      python main.py
      ```

2. **Visualizações**:
    - As visualizações podem ser geradas para explorar a importância das features e as distribuições de dados dos clientes.

3. **Exemplo de previsão**:
    - Após treinar o modelo, você pode usar novos dados para prever se um cliente aceitará a campanha de marketing:
    ```python
    # Exemplo de uso
    nova_previsao = modelo.predict(novos_dados)
    print(f"Previsão: {nova_previsao}")
    ```

---

### Base de Dados

A base de dados utilizada contém informações como:

- **Demográficas**: idade, renda, estado civil, etc.
- **Histórico de compras**: quantidade gasta em produtos de carne, frutas, peixes, etc.
- **Histórico de campanhas anteriores**: se o cliente aceitou ou não campanhas anteriores.

A coluna alvo é `Response`, que indica se o cliente aceitou a última campanha de marketing.

---

### Modelo de IA

O modelo utilizado é o **Random Forest Classifier**. Aqui estão alguns detalhes:

- **Algoritmo**: Random Forest
- **Métrica de avaliação**: Acurácia, F1-Score
- **Pré-processamento**:
    - Divisão de treino/teste
    - Normalização dos dados
- **Importância das Features**:
    - Utilizamos gráficos para identificar quais variáveis tiveram mais impacto nas decisões do modelo.

---

### Resultados

Os resultados principais obtidos até agora incluem:

- **Acurácia**: [Insira a acurácia obtida]
- **F1-Score**: [Insira o F1-Score]
- **Importância das Features**:
    - ![image](https://github.com/user-attachments/assets/634ff46c-2374-46f8-940b-7ef05fca458e)


### Visualizações

- Gráficos de aceitação por campanha.
- Distribuição de idade dos clientes que aceitaram ou não a última campanha.

---
### Integrantes
550373 - Leonardo Yuuki Nakazone

99119 - Leonardo Blanco Pérez Ribeiro

98082 - Paulo Henrique Luchini Ferreira

97999 - Gustavo Moreira Gonçalves

552184 - Daniel Soares Delfin


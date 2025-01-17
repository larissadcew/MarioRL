# 🕹 MarioRL

![Imagem de Fundo](data/mariofundo.png)

## 🎯 Descrição

**MarioRL** é um agente de **Aprendizado por Reforço** desenvolvido para aprender a jogar **Super Mario Bros** de forma autônoma. Utilizando técnicas avançadas de aprendizado profundo e otimizações eficientes, MarioRL busca alcançar um desempenho comparável aos modelos mais robustos com uma fração dos parâmetros.

## 🧠 Algoritmos de Aprendizado

### 1. **Rede de Q-Duplo com Dueling**
- **Técnica avançada de aprendizado profundo**: Combina redes neurais duplas para estimar os valores de ação de maneira mais precisa.
- **Melhora a eficiência de aprendizagem**: Reduz o viés na estimativa do valor de ação, promovendo um aprendizado mais estável e eficiente.

### 2. **Otimização de Política Proximal**
- **Estratégia robusta de melhoria de política**: Garante atualizações de política seguras, evitando grandes mudanças que possam degradar o desempenho.
- **Dinâmicas de aprendizado estáveis**: Promove um treinamento mais consistente e confiável, facilitando a convergência do agente.

## ▶ Execução do Projeto

### 🏃‍♂️ Avaliar Agente Pré-treinado

Para avaliar o desempenho do agente treinado, execute o script de teste:

```bash
python test.py

```

### 🚴‍♂️ Treinar Novo Agente
Para iniciar o processo de treinamento de um novo agente, utilize o seguinte comando:

```bash
python train.py
```

### 📓 Exploração Interativa
Explore o Jupyter Notebook para visualizar e interagir com o projeto de forma mais detalhada:

### [Jupyter Notebook](MarioRL.ipynb)

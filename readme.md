Detecção de COVID-19 em Imagens de Tomografia Computadorizada usando Deep Learning
Este repositório contém o código-fonte, a documentação e o histórico de desenvolvimento do projeto final da disciplina de Machine Learning. O objetivo principal é desenvolver e analisar comparativamente modelos de Deep Learning para a classificação binária automática de imagens de tomografia computadorizada (CT) de tórax em duas categorias: "COVID-19" e "Não-COVID".

A solução aborda desde o pré-processamento de imagens médicas até a aplicação de técnicas avançadas como Transfer Learning, comparando a eficácia de diferentes arquiteturas (CNNs) e frameworks.

---

🧠
 Visão Geral da Solução
O projeto foi desenvolvido seguindo um fluxo iterativo, explorando diferentes abordagens técnicas para resolver o problema de classificação. A solução final consiste em um comparativo entre dois frameworks líderes de mercado, utilizando pesos pré-treinados na base ImageNet:

Abordagem PyTorch: Utilização da arquitetura ResNet18. Focada no controle granular do loop de treinamento, ideal para compreensão acadêmica dos processos de retropropagação e otimização.
Abordagem TensorFlow/Keras (Solução Final): Utilização da arquitetura EfficientNetB0. Focada na eficiência computacional e facilidade de implementação para produção, empregando técnicas de Data Augmentation robustas e callbacks para evitar overfitting.

O modelo baseado em EfficientNetB0 foi selecionado como a solução final devido ao seu melhor equilíbrio entre custo computacional e métricas de desempenho (Acurácia e AUC).

---

📂
 Estrutura do Repositório
O projeto está organizado da seguinte forma para facilitar a navegação e a compreensão do histórico de desenvolvimento:
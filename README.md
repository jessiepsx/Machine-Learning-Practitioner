# 🐛 Classificação de Pragas Agrícolas com Deep Learning  

Este projeto foi desenvolvido no **Bootcamp BairesDev - DIO**, com o objetivo de **classificar imagens de pragas agrícolas** utilizando **Redes Neurais Convolucionais (CNNs)** e **Transfer Learning com VGG16**.  

A ideia central é treinar modelos de **Visão Computacional** capazes de identificar pragas a partir de imagens, apoiando soluções para o setor agrícola e contribuindo para **agricultura inteligente e sustentável**.  

---

## ⚙️ Tecnologias Utilizadas  

- **Python 3.12**  
- **TensorFlow / Keras** – construção, treino e avaliação das redes neurais.  
- **Matplotlib** – visualização de métricas de treino e resultados.  
- **NumPy** – manipulação numérica dos dados.  
- **Google Colab** – ambiente de execução e treinamento em GPU.  

---

## 🚀 Etapas do Projeto  

1. **Preparação dos Dados**  
   - Normalização das imagens.  
   - Divisão em treino, validação e teste (70% / 15% / 15%).  

2. **Modelo CNN do Zero**  
   - Arquitetura própria com camadas **Conv2D, MaxPooling, Dropout e Dense**.  
   - Atingiu **~84% de acurácia** no conjunto de teste.  

3. **Transfer Learning com VGG16**  
   - Utilização do modelo **pré-treinado no ImageNet**.  
   - Camadas convolucionais congeladas + nova camada densa para classificação binária.  
   - Atingiu **~90% de acurácia** no conjunto de teste.  

4. **Avaliação e Visualização**  
   - Curvas de **val_loss** e **val_accuracy** comparando os modelos.  
   - Teste em imagens reais para verificar probabilidades de classificação.  

---

## 📊 Resultados  

- **CNN do Zero** → Test Accuracy: **84.37%**  
- **VGG16 (Transfer Learning)** → Test Accuracy: **90.62%** ✅  

O uso de Transfer Learning se mostrou mais eficiente e robusto para o problema.  

---

## 📚 Aprendizados  

- Construção de **Redes Neurais Convolucionais (CNNs)** do zero.  
- Aplicação de **Transfer Learning** com o modelo VGG16.  
- Técnicas de **pré-processamento de dados** (normalização e divisão em treino/validação/teste).  
- Uso de métricas de avaliação para comparar diferentes arquiteturas de redes neurais.  
- Visualização dos resultados com **gráficos de acurácia e perda** durante o treinamento.  

---


## 📬 Contato  

👩‍💻 Desenvolvido por **Jéssica Pereira**  
🔗 [LinkedIn](https://www.linkedin.com/in/jessiepsx)  
📂 [GitHub](https://github.com/jessiepsx)  

---



# 🖼️ Conversão de Imagem: Colorida → Tons de Cinza → Binarizada (Preto e Branco)

Este projeto tem como objetivo demonstrar, de forma simples e prática, como transformar uma imagem colorida em tons de cinza e em uma imagem binarizada (preto e branco), utilizando Python com OpenCV e Matplotlib no Google Colab.

---

## 📌 Tecnologias utilizadas

- Python 3
- Google Colab
- OpenCV (`cv2`)
- Matplotlib
- PIL (opcional)

---

## 🧠 O que o código faz?
Etapa 1: Lê a imagem colorida enviada pelo usuário.

Etapa 2: Converte a imagem para tons de cinza (valores de 0 a 255).

Etapa 3: Aplica binarização com um limiar (threshold), transformando em uma imagem com apenas preto (0) e branco (255).

Etapa 4: Exibe as três versões da imagem: colorida, em tons de cinza e binarizada.

---

## 🖼️ Resultado esperado
As três versões da imagem são exibidas lado a lado:

- Imagem Colorida

- Imagem em Tons de Cinza (Grayscale)

- Imagem Binarizada (Preto e Branco)

---

## 📚 Referência teórica
O algoritmo de binarização utiliza o método de threshold fixo, onde um valor limite é definido (geralmente 127) para separar os pixels claros e escuros:

- Se pixel < 127: preto (0)

- Se pixel ≥ 127: branco (255)

Esse método é simples, mas eficaz para imagens com boa iluminação.

---

# 👨‍💻 Autor
Victor Henrique Estrella Carracci

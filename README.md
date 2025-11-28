
---

# ✅ **Face Detection (OpenCV)**

```md
# 👁️ Face Detection com OpenCV

Este projeto detecta rostos em imagens utilizando as ferramentas da biblioteca OpenCV.  
Foi desenvolvido como parte do meu aprendizado em visão computacional e processamento de imagens.

A detecção é feita utilizando classificadores Haar Cascade, um método clássico, leve e eficiente para estudos iniciais.

---

## 🎯 Objetivo
Criar um detector de rosto simples que marque, em uma imagem, onde foram identificados rostos humanos.

---

## 🧠 Conceitos Utilizados
- OpenCV  
- Haar Cascades  
- Processamento básico de imagens  
- Conversão de imagem para escala de cinza  
- Desenho de bounding boxes  

---

## 🚀 Como executar
Instale as dependências:

pip install opencv-python
python detect.py

---

🔧 Tecnologias

- Python 3
- OpenCV

---

📝 Funcionamento
1. A imagem é carregada
2. Convertida para tons de cinza
3. O classificador Haar é aplicado
4. Cada rosto encontrado recebe um retângulo desenhado

---

📌 Possíveis melhorias
- Implementar detecção via DNN (modelo Caffe, TensorFlow ou ONNX)
- Detecção de olhos e expressões
- Aplicar em vídeos e webcam
- Converter para um módulo reutilizável

---

📘 Status
✔ Versão inicial concluída

# Skin Lesion Classifier (CNN - MobileNetV2)

Proyecto academico de Deep Learning para la **clasificación de lesiones de piel** utilizando una red neuronal convolucional (CNN) con **Transfer Learning** basado en MobileNetV2.

## Este proyecto es únicamente con fines educativos y **no debe usarse para diagnóstico médico real**.

---
## Detalles del modelo:
- El objetivo de este proyecto es desarrollar un modelo capaz de clasificar imágenes de lesiones en la piel en distintas categorías y peligrosidades, para una deteccion de posibles lesiones cancerosas.
- Dataset HAM10000 (Contiene 10,000 imágenes dermatoscópicas de diferentes tipos de lesiones de piel)
- Accuracy Obtenido: 78.22%
- Loss Obtenido: 0.5965
- Se entreno el modelo utilizando MobileNetV2 con 2 etapas de File Tuning para descongelar distintas cantidades de capas (Transfer Learning)

### Clonar repositorio
```bash
git clone https://github.com/[tu-usuario]/skin-lesion-classifier-cnn_mobilenetv2.git
cd skin-lesion-classifier-cnn_mobilenetv2

# VR-Watson-Sura

# GUIA DE VISUAL RECOGNITION
IBM Watson Visual Recognition es una herramienta que utiliza algoritmos de machine learning, permitiendo a los usuarios identificar automáticamente sujetos, objetos, contenidos en la imagen, organizar y clasificar dichas imágenes en categorías lógicas.
Este servicio es muy intuitivo, sus resultados son detallados y rápidos debido a que los modelos están ampliamnete entrenados.

### 1. Pre-requisitos 📋
Tener una cuenta IBM Cloud, en caso de no tenerla por favor creela.

[CREAR CUENTA IBM CLOUD](https://cloud.ibm.com/registration)

### 2. Visual Recongition por medio Watson Studio en IBM CLOUD 🚀

### Caso de uso:
Las empresas están resolviendo sus desafíos únicos mediante el uso de modelos personalizados para reconocer cualquier objeto, escena o atributo. Para este caso utilizaremos modelos personalizados para generar automáticamente estimaciones de los costos de reparación basados en imágenes de daños en el automóvil enviadas a medida.

#### Paso 1:
Selecciona el servicio de Visual Recognition, este se puede identificar con el siguiente icono ![Icono 1](https://user-images.githubusercontent.com/56199403/79884639-06893600-83bb-11ea-9d2e-381ac03c1d58.jpg).

#### Paso 2:
Posteriormente debes dar clic en “Launch Watson Studio”, y en la nueva pestaña que se cargó debes seleccionar el tipo de modelo que deseas utilizar, para esta guía se utilizó “Classify Images”.

#### Paso 3:
Ahora procedemos a subir al modelo el set de imágenes positivas, las cuales proporcionarán ejemplos de imágenes reales de objetos para clasificar como miembros de esa clase.

*Nota💡 : Hay que tener en cuenta que el número mínimo recomendado de imágenes para tener en los conjuntos de imágenes positivas antes de evaluar los resultados de la prueba es de 50 imágenes y los formatos que acepta el modelo son .jpeg, .png, o .zip*

#### Paso 4:
Ahora seleccionamos la clase “Negative” e ingresamos el set de imágenes negativas, que son ejemplos de imágenes reales de objetos para NO ser clasificados como miembros de esa clase.

#### Paso 5:
Una vez cargados los sets de imágenes al modelo, se procede a entrenar seleccionando el siguiente botón 

## Construido con 🛠️
IBM Cloud, Visual Recognition[VR](https://cloud.ibm.com/catalog/services/visual-recognition)


## Wiki 📖
Para más información [Watson-Visual Recognition](https://www.ibm.com/co-es/cloud/watson-visual-recognition)


## Autores ✒️
Team Cloud IBM



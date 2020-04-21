# VR-Watson-Sura

# GUIA DE VISUAL RECOGNITION
IBM Watson Visual Recognition es una herramienta que utiliza algoritmos de machine learning, permitiendo a los usuarios identificar automáticamente sujetos, objetos, contenidos en la imagen, organizar y clasificar dichas imágenes en categorías lógicas.
Este servicio es muy intuitivo, sus resultados son detallados y rápidos debido a que los modelos están ampliamnete entrenados.

### Pre-Requisitos 📋


#### Primero.

Iniciar sesión en IBM Cloud, en caso de que no se cuente con una cuenta, crearla en este enlace https://cloud.ibm.com/registration

#### Segundo.

En la sección de catálogo debe buscar Visual Recognition y se selecciona dicho servicio

![Image 3](https://user-images.githubusercontent.com/56199403/79892028-769db900-83c7-11ea-8607-5cbdc9a7ccce.jpg)

#### Tercero.

Para crear el servicio lo primero se realiza es seleccionar la región, para esta guía se seleccionó Dallas, posteriormente se selecciona el tipo de plan que se acomode mejor a sus necesidades y por último se le asigna un nombre al servicio. 

![image 4](https://user-images.githubusercontent.com/56199403/79892286-f2980100-83c7-11ea-873f-e44f6d76e44f.jpg)

#### Cuarto.

Por último se selecciona la opción de "Create".


### 2. Visual Recongition por medio Watson Studio en IBM CLOUD 🚀
### Caso de uso:
Las empresas están resolviendo sus desafíos únicos mediante el uso de modelos personalizados para reconocer cualquier objeto, escena o atributo. Para este caso utilizaremos modelos personalizados para generar automáticamente estimaciones de los costos de reparación basados en imágenes de daños en el automóvil enviadas a medida.

#### Paso 1:
Se debe seleccionar el servicio de Visual Recognition, este se puede identificar con el siguiente icono ![Icono 1](https://user-images.githubusercontent.com/56199403/79884639-06893600-83bb-11ea-9d2e-381ac03c1d58.jpg).

#### Paso 2:
Posteriormente se debe dar clic en “Launch Watson Studio”, y en la nueva pestaña que se cargó seleccionamos el tipo de modelo que se desea utilizar, para esta guía se utilizó “Classify Images”.

![Image 1](https://user-images.githubusercontent.com/56199403/79890486-2f162d80-83c5-11ea-8011-261da082c822.jpg)

#### Paso 3:
Ahora procedemos a subir al modelo el set de imágenes positivas, las cuales proporcionarán ejemplos de imágenes reales de objetos para clasificar como miembros de esa clase.

![Image 2](https://user-images.githubusercontent.com/56199403/79891059-0cd0df80-83c6-11ea-9b19-ba8c7c4bd0a5.jpg)

*Nota: Hay que tener en cuenta que el número mínimo recomendado de imágenes para tener en los conjuntos de imágenes positivas antes de evaluar los resultados de la prueba es de 50 imágenes y los formatos que acepta el modelo son .jpeg, .png, o .zip* 💡

#### Paso 4:
Una vez cargado el set positivo, se selecciona la clase “Negative” e ingresamos el set de imágenes negativas, que son ejemplos de imágenes reales de objetos para NO ser clasificados como miembros de esa clase.

#### Paso 5:
Una vez cargados los sets de imágenes al modelo, se procede a entrenar seleccionando el siguiente botón ![Icono 2](https://user-images.githubusercontent.com/56199403/79891459-a26c6f00-83c6-11ea-8cf5-c8d87b52adec.jpg)

#### Paso 6:
Una vez entrenado el modelo, seleccionamos la opción de "Test" y probamos el modelo

## Construido con 🛠️
IBM Cloud, Visual Recognition: [VR](https://cloud.ibm.com/catalog/services/visual-recognition)



## Wiki 📖
Para más información [Watson-Visual Recognition](https://www.ibm.com/co-es/cloud/watson-visual-recognition)


## Autores ✒️
Team IBM Cloud




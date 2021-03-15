# Cassava Leaf Disease Detection


Este proyecto fue presentado en la competición de Kaggle con la que comparte nombre. Presentado por una universidad Makerere, de Uganda, su objetivo es clasificar fotografías de la planta de la yuca para identificar posibles enfermedades y así facilitar estos cultivos en la zona. La yuca, importado su cultivo de Sudamérica, supone gran parte de la agricultura africana y las enfermedades detectadas implican inmensas pérdidas o enfermedades en los consumidores.

Para el desarrollo de este proyecto se hace uso de redes de neuronas convolucionales, concretamente de una EfficientNet-B5 conectada a un perceptrón multicapa y un tamaño de entrada para la imagen de 528x528 (el indicado en el trabajo en el que se presenta este tipo de red). Empleando data augmentation, transfer learning y TTA se logra un porcentaje de clasificación correcta del 89.3% para cinco clases, a algo menos de un 1% del podio en la tabla de clasificación privada. 

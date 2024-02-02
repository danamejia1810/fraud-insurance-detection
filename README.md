# Técnicas de Machine Learning para la detección del fraude: Caso de estudio en el sector asegurador de automóviles.


## Descripción
Este proyecto explora la aplicación de técnicas avanzadas de machine learning para detectar el fraude en seguros de automóviles. Utilizando un conjunto de datos desbalanceado, se comparan varios modelos con algoritmos de Machine Learning y se comparan con los resultads obtenidos de implementar técnicas de balanceo, búsqueda de hiperparámetros y selección de caracteristicas óptimas para identificar la estrategia más efectiva. Este repositorio hace parte del trabajo final del master de Ciencia de Datos de la UOC. 

## Problemática
El fraude en seguros de automóviles representa un desafío significativo para la industria y la detección eficaz de ésta es crítica. En un mundo cada vez más digital es necesario que las empresas deban adoptar medidas que ayuden a reducir las pérdidas monetarias que sufren por causa del fraude e identificar patrones en los procesos de reclamos y de contratación (Hakim, 2020). Aunque ellas emplean personal dedicado a identificar este tipo de comportamientos, el proceso puede llegar a tomar más tiempo del necesario, son más complejos y pueden generar altos costos de mantenimiento por lo que deben estar integrados de manera que puedan traer respuestas más rápidas. Esto es un desafío prominente en el ramo de seguros de automóviles, debido a la escasez de información de los clientes en cuanto a sus conductas financieras para conocer la existencia previa de actividades fraudulentas o que pueda facilitar la ocurrencia de ellas. 

## Conjunto de datos
Se obtuvieron el conjunto de datos de la plataforma pública de Kaggle y en donde tambien se puede encontrar en la platafoma con las mismas características llamada Medeley Data, [accesible aquí](
https://data.mendeley.com/datasets/992mh7dk9y)

## Metodología
- Modelos evaluados: Rgresión Logística, Decision Tree, Random Forest, Ada Boost y Gradient Boosting.
- Técnicas de balanceo: Random Under Sampler, Random Over Sampler, SMOTE y SMOTE- TOMEK.
- Métodos de optimización: RandomSearchCV para optimización de hiperparámetros, RFECV para selección de características.

## Herramientas
Se utilizó Python como herramienta para el código y Ganttpro para el cronograma de actividades.

## Resultados
Los resultados muestran que la combinación de Random Under Sampler con Ada Boost ofrece el equilibrio más óptimo que se encuentra entre precisión y recall, destacando la importancia de la selección adecuada de características y la optimización de hiperparámetros.

## Conclusión
Este trabajo aporta a la lucha contra el fraude en seguros de automóviles, demostrando el potencial de las técnicas de machine learning para mejorar la detección de fraude y contribuyendo al desarrollo de estrategias más robustas y justas. Ofrece una base para futuras investigaciones y desarrollos en el campo.

## Cómo Contribuir
Las contribuciones son bienvenidas. Por favor, envíen sus pull requests o abran un issue para discutir lo que le gustaría cambiar.

## Licencia
[MIT](https://choosealicense.com/licenses/mit/)

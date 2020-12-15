# Práctica general: Lending Club, versión mejorada 

Información de los integrantes del grupo:

Nombre y apellidos: Gabriel Blanco García
Correo electrónico: gabriel.blanco@cunef.edu

Nombre y apellidos: Michelle Ferrín Meilá
Correo electrónico: michelle.ferrin@cunef.edu

El objetivo de esta práctica construir modelos de Machine Learning para la correcta 
asginación del crédito a solicitantes de préstamos, y minimizar las pérdidas. Se trabaja con
los datos de https://www.lendingclub.com/

Diferencias con la primera versión:
1. Se optimizan los hiperparámetros del mejor modelo, utilizando un conjunto
de validción.
2. Se añaden más métricas para explicar mejor el modelo ganador.
3. Se utiliza el paquete shap para interpretar el modelo ganador. 
4. Se añade un notebook que simula la puesta en producción del modelo ganador, con
el fin de poner a prueba el código del trabajo.
5. Se ha creado un archvo adicional dentro de "src" que recopila funciones que hemos
programado para el cálculo de algunas métricas.

Información sobre las carpetas y su contenido 
- Data: carpetas con los directorios de los datos del trabajo, están vacías para poder subirlas. 

- Environment: contiene el entorno utilizado para el trabajo.

- html: los notebooks del trabajo, guardados en formato html.

- images: contiene una imagen que se inserta en el notebook de Feature Engineernig, puesto que no fue 
posible insertarla desde web.

- models: contiene la carpeta trained_models, con los modelos entrenados. Está vacía porque algunos de ellos 
son extremadamente pesados

- notebooks : cada uno de los notebooks del trabajo, ordenados en función del flujo de trabajo que ha 
seguido el proyecto

- pipelines: contiene los pipelines empleados a lo largo de la fase de modelado, guardados como .sav

- references: contiene un archivo con las referencias y el material empleado en el trabajo.

- src: contiene dos archivos  .ipynb con las funciones que se generan y utilizan a lo largo del proyecto. 
El archivo lectura y preprocesado recopila todas las funciones que se emplean para modificar el dataset, y la función general que se implementa en el "exámen de código"
El archivo tablas y gráficos contiene funciones de tipo explicativo y gráfico, para calcular tablas porcentuales, etc.
El archivo plots_metricas contiene funciones para hacer gráficos de las métricas
de los modelos.
   

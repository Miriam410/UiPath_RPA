# UiPath_RPA 

## Ejercicio1:

### Empezar un nuevo proyecto y crear una secuencia inicial.
#### 0.0) Crear una variable de tipo String llamada nombre.
#### 0.1) Crear una variable de tipo Int32 llamada edad.
#### 0.2) Crear una actividad en UiPath llamada “Input Dialog”. 
       - Agregar en “Dialog Title”: Input Dialog.
       - Agregar en “Input Label”: Ingrese su nombre.
       - Almacenar en la variable nombre el resultado.
#### 0.3) Crear una actividad en UiPath llamada “Input Dialog”. 
       - Agregar en “Dialog Title”: Input Dialog.
       - Agregar en “Input Label”: Ingrese su edad.
       - Almacenar en la variable edad el resultado.
#### 0.4) Crear una nueva secuencia individual que se llame “ImprimirResultados”
#### 0.5) Crear dos argumentos en la secuencia “ImprimirResultados” (Donde posteriormente vamos a guardar los valores de nombre y edad)
#### 0.6) En la secuencia principal, crear la actividad “Invoke Workflow File” y llamar a la secuencia “imprimirResultados”
#### 0.7) Importar argumentos. Pasar los valores de nombre y edad a los argumentos de la secuencia “ImprimirResultados”
#### 0.8) En la secuencia ImprimirResultados, imprimir los valores de los argumentos.

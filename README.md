# PC2-AdvancedAI
PC2 del curso de advanced artificial inteligence (2022-02)

## Pregunta 1: Comparacion del makespan conseguido entre el algoritmo random hill climbing nswap y el evolutivo en 9 minutos (Instancia ab7)

### Random Restart Hill Climbing Nswap 

Makespan: 737

Schedule:

![alt text](https://raw.githubusercontent.com/SebsPER/PC2-AdvancedAI/main/pictures/hill.jpg)

Progress (Makespan vs Iterations):

![alt text](https://raw.githubusercontent.com/SebsPER/PC2-AdvancedAI/main/pictures/hillProgress.jpg)

### Algoritmo Evolutivo

Makespan: 808

Iterations: 90

Schedule:

![alt text](https://raw.githubusercontent.com/SebsPER/PC2-AdvancedAI/main/pictures/evo.jpg)

Progress (Makespan vs Iterations):

![alt text](https://raw.githubusercontent.com/SebsPER/PC2-AdvancedAI/main/pictures/evoProgress.jpg)

## Pregunta 2: Comparacion del makespan conseguido entre el algoritmo evolutivo con y sin recombination en 9 minutos (Instancia ab7)

### Algoritmo Evolutivo con Recombination

Makespan: 806

Iterations: 32

El algoritmo con recombination demuestra ser mas pesado computacionalmente debido a que tan solo es capaz de realizar 32 iteraciones a través de 9 minutos de ejecución. Sin embargo, logró conseguir un makespan mejor que el evolutivo con nswap, tan solo por 2 puntos. Teniendo eso en cuenta, se podría concluir que el algoritmo con recombination tiene una estrategia mas efectiva ya que logra mayor progreso con menos itereaciones. Se puede verificar en el gráfico del recombination que logra realizar un progreso constante a través de la ejecución del algoritmo. El progreso es bastante regular. Por otro lado, el algoritmo evolutivo con nswap realiza mas iteraciones pero logra progresar dando saltos mas repentinos y se beneficia mas de tener amplio tiempo de ejecición para hacer algun descubrimiento.

Schedule:

![alt text](https://raw.githubusercontent.com/SebsPER/PC2-AdvancedAI/main/pictures/evo_recom.jpg)

Progress (Makespan vs Iterations):

![alt text](https://raw.githubusercontent.com/SebsPER/PC2-AdvancedAI/main/pictures/evo_recomProgress.jpg)


# Resolución de Problemas — Adición

## Etapa #1: Análisis del problema:

### Transcripción del problema:

- Pedir dos numeros y mostrar la suma

### Refinamiento del problema e Hipótesis de trabajo:

- El programa pide al usuario que ingrese dos numeros enteros y luego este va a mostrar la suma resultante en pantalla

### Modelo IPO:

- Z X Z --> Adición --> Z

## Etapa #2 Diseño de la Solución

### Léxico del Algoritmo

- a,b ∈ Z

### Representación del Algoritmo

```
#include <iostream>

int main()
{
	int num1, num2;
	std::cout << "Ingrese el primer numero:\n";
	std::cin >> num1;
	std::cout << "Ingrese el segundo numero:\n";
	std::cin >> num2;
	std::cout << "La suma de los dos numeros es: " << num1 + num2;
}
```

### -Representación visual.

![Diagrama de flujos](https://cdn.discordapp.com/attachments/683848110006730753/756149595960115290/unknown.png)

### -Representación textual

1: Mostrar "ingrese el primer numero:".

2: Leer un entero y almacenarlo en num1.

3: Mostrar "ingrese el segundo numero:".

4: Leer un entero y almacenarlo en num2.6

5: Mostrar "la suma de los dos numeros es:"

6: Mostrar suma de num1 y num2

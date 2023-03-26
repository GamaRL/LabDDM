# Prácticas de Deseño Digital Moderno

## Índice de Prácticas
1. [Implementación de compuertas básicas en la plataforma Quartus II, en modo gráfico](practica01/)
2. [Construcción de funciones booleanas en la plataforma Quartus II, en modo gráfico](practica02/)
3. [Aplicación de Funciones Lógicas](practica03/)
4. [Lenguaje de descripción de hardware VHDL](practica04/)

## Estructura de cada práctica
- `build/`: En este directorio se coloca la compilación de `LaTeX`.
- `img/`: El directorio de imágenes.
- `sections/`: Las diferentes secciones a desarrollar de la práctica.

## Compilación de una práctica
1. Dirigirse al directorio de la práctica.
2. Si no existe el directorio `build/`, crearlo.
3. Ejecutar el comando
```bash
pdflatex --output-dir=build main
```
4. El archivo será `build/main.pdf`

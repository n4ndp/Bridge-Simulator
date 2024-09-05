# **Bridge Simulator**

**Una aplicación interactiva en 2D para construir puentes utilizando diferentes materiales y técnicas. Diseña estructuras sólidas y estables para soportar vehículos en varios escenarios desafiantes.**

## **Tabla de Contenidos**

1. [Introducción](#introducción)
2. [Motivación](#motivación)
3. [Características](#características)
4. [Relevancia para el Curso](#relevancia-para-el-curso)
5. [Tecnologías Utilizadas](#tecnologías-utilizadas)
6. [Integrantes del Equipo](#integrantes-del-equipo)

## **Introducción**

**Bridge Simulator** es un juego de simulación basado en física en 2D, inspirado en el popular juego **Poly Bridge**. El objetivo es diseñar y construir puentes utilizando recursos limitados, como vigas de madera, vigas de acero y cables, para garantizar que los vehículos puedan cruzar de un lado a otro sin que la estructura colapse. El juego desafía a los jugadores a pensar críticamente y aplicar principios de física e ingeniería para crear diseños de puentes funcionales y eficientes.

### **Gameplay de Referencia**

Para tener una idea visual de lo que buscamos desarrollar, aquí tienes un video de gameplay de **Poly Bridge**:

[![Gameplay de Poly Bridge](https://img.youtube.com/vi/d_2KPqC4b1s/0.jpg)](https://youtu.be/d_2KPqC4b1s?t=375)

## **Motivación**

La motivación para crear **Bridge Simulator** surge del interés por explorar y aplicar los principios de la simulación física y la ingeniería estructural. Al desarrollar este juego, nuestro objetivo es proporcionar una herramienta atractiva y educativa que resalte las aplicaciones prácticas de la informática en la resolución de problemas de ingeniería del mundo real.

## **Características**

- **Mecánicas de Construcción de Puentes**: Utiliza diversos materiales como madera, acero y cables para construir puentes.
- **Simulación Física Realista**: Potenciado por Box2D, el juego simula fuerzas realistas como la gravedad, la tensión y la compresión.
- **Niveles Desafiantes**: Múltiples niveles con diferentes dificultades y desafíos únicos, como presupuestos limitados y materiales restringidos.
- **Visualización de Retroalimentación**: Visualización en tiempo real del estrés en los componentes del puente para ayudar a los jugadores a mejorar sus diseños.
- **Interfaz de Usuario Intuitiva**: Controles fáciles de usar y una interfaz limpia para una experiencia de juego fluida.
- **Opción de Expansión con OpenGL**: Aunque utilizaremos **SFML** para el renderizado 2D, **OpenGL (con GLFW)** sigue siendo una opción viable para futuras expansiones del juego.

## **Relevancia para el Curso**

Este proyecto es altamente relevante para nuestro curso de Computación Gráfica ya que incorpora varios conceptos fundamentales:

- **Renderizado Gráfico en 2D**: Utilizando **SFML** para el renderizado y la visualización del entorno del juego en dos dimensiones.
- **Simulaciones Basadas en Física**: Implementación de **Box2D** para simular comportamientos físicos realistas, crucial para comprender cómo se calculan y representan las simulaciones físicas en gráficos computacionales.
- **Diseño de Interfaz de Usuario**: Diseño de una interfaz de usuario intuitiva con **ImGui** que permite a los jugadores interactuar con el juego y construir puentes con facilidad.

## **Tecnologías Utilizadas**

- **C++**: Lenguaje de programación principal para la lógica del juego e implementación.
- **SFML**: Librería para manejar gráficos 2D, entrada del usuario y renderizado en tiempo real.
- **Box2D**: Un potente motor de física 2D utilizado para simular fuerzas y comportamientos realistas.
- **ImGui**: Librería GUI de modo inmediato para construir una interfaz de usuario simple y efectiva.
- **Git y GitHub**: Herramientas para control de versiones y colaboración.

## **Integrantes del Equipo**

- Fernando Adriano Choqque Mejia

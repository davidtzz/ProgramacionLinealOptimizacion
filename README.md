Método Gráfico de Programación Lineal (Forma Estándar)
=========================================================

Este proyecto implementa un **solucionador de problemas de Programación Lineal** con **dos variables**, utilizando el **método gráfico**.

Permite al usuario ingresar una función objetivo y un conjunto de restricciones en **forma estándar**, y muestra tanto el resultado numérico como la **representación gráfica** de la región factible y el punto óptimo.

Objetivo del Proyecto
------------------------

El propósito de este programa es **visualizar y resolver problemas de maximización** de funciones lineales sujetas a restricciones lineales de la forma:

**Maximizar:** Z = c₁x₁ + c₂x₂

**Sujeto a:** a₁x₁ + a₂x₂ ≤ bx₁, x₂ ≥ 0

El método gráfico es ideal para problemas de **dos variables**, ya que permite **representar geométricamente** la región factible y observar cómo se determina el punto óptimo.

Características Principales
------------------------------

*   **Entrada interactiva:** el usuario ingresa la función objetivo y las restricciones.
    
*   **Visualización completa:**
    
    *   Gráficas de todas las restricciones.
        
    *   Sombreado de las zonas válidas hacia abajo (≤).
        
    *   **Región factible** resaltada en verde.
        
    *   **Punto óptimo** marcado en rojo.
        
*   **Cálculo automático** del punto de intersección y valor máximo de la función objetivo.
    
*   **Forma estándar:** solo admite problemas de **maximización** con restricciones del tipo ≤.
    

Ejemplo de Ejecución
-----------------------

### Entrada:

Ingrese los coeficientes de la función objetivo (c1 c2): 3 5

¿Cuántas restricciones desea ingresar?: 2

Restricción 1: formato -> a1 a2 <= b

Ingrese los valores a1 a2 b: 1 2 8

Restricción 2: formato -> a1 a2 <= b

Ingrese los valores a1 a2 b: 3 2 12

### Salida:

\========== RESULTADO ==========

R/ x1 = 0.00, x2 = 4.00

Valor óptimo de Z = 20.00

### Gráfica generada:

*   Las rectas de las restricciones.
    
*   Las zonas válidas sombreadas hacia abajo.
    
*   La **región factible** en verde claro.
    
*   El **punto óptimo** en rojo.
    

Tecnologías Utilizadas
--------------------------

*   **Python 3**
    
*   **Sympy** — para resolver sistemas de ecuaciones lineales.
    
*   **Matplotlib** — para la representación gráfica y sombreado.
    
*   **NumPy** — para manejo de cálculos y matrices numéricas.
    

Ejecución
-----------

1.  pip install numpy sympy matplotlib
    
2.  python pl\_forma\_estandar\_sombreado\_correcto.py
    

Autores
----------

**Desarrollado por:**

*   David Felipe Tovar Zurita
    
*   Jhon Alejandro García Pareja
    

Próximas Etapas
------------------

Este proyecto forma parte de una serie de entregas progresivas en las que se incluirán:

*   Extensión a más de dos variables (**método simplex**).
    
*   Casos de **minimización** y restricciones mixtas (≥, =).
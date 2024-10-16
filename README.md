Práctica de aula 7 (PA07). Morfometría de Cuencas y Procesos
Fluviales<small><br>Geomorfología (GEO-114)<br>Universidad Autónoma de
Santo Domingo (UASD)<br>Semestre 2024-02</small>
================
El Tali
2024-10-14

Versión HTML (quizá más legible),
[aquí](https://geomorfologia-master.github.io/sistema-fluvial-morfometria-cuenca-basica/README.html)

# Fecha/hora de entrega

**15 de octubre de 2024, 11:59 pm.**

# Objetivo

El objetivo de esta práctica es aplicar conceptos de geomorfología
fluvial y morfometría de cuencas, utilizando herramientas de análisis
geomorfológico. Se espera que los estudiantes consulten los libros de
*Geomorfología* de Mateo Gutiérrez Elorza y *Geomorfología* de Javier de
Pedraza para profundizar en el contenido teórico.

# Materiales

- Libro: Gutiérrez Elorza, M. (2008). Geomorfología. España: Pearson
  Educación.
- Libro: Pedraza, J. d., Carrasco González, R. M. (1996). Geomorfología:
  principios, métodos y aplicaciones. España: Rueda.
- Mapa de una cuenca hidrográfica y vegetal para dibujar encima.
- (Opcional) Software de Sistemas de Información Geográfica (SIG).
- Calculadora.

En el último apartado de esta práctica denominado “**Informe final**”,
tienes un mandato que debes leer antes comenzar la práctica. Lee todos
los apartados antes de comenzar.

# Ejercicio 1. Consulta bibliográfica

Investiga los conceptos de geomorfología fluvial y morfometría de
cuencas en los libros mencionados. Debes centrarte en los siguientes
temas, revisando en los dos libros, el de Gutiérrez Elorza (2008) y el
de De Pedraza (1996):

- **Breve historia**: Principales autores clásicos y recientes.
- **El sistema fluvial**: Revisa los conceptos básicos (río, canal,
  escorrentía), el sistema fluvial idealizado, las variables y su
  relevancia en los distintos intervaos temporales.
- **Fundamentos hidrológicos**: Revisa la sección correspondiente del
  libro de De Pedraza, específicamente sobre generación y concnetración
  de escorrentía, régimen hídrico, crecidas y estiajaes, el hidrograma
  de crecida.
- **Morfometría de cuencas y redes de drenaje**: Revisa los apartados o
  el contenido de morfometría de cuencas, especialmente los conceptos de
  área de cuenca, orden de red, razón (relación) de bifurcación,
  densidad de drenaje, y todos los demás parámetros morfométricos de
  cuenca sy redes.

De cada tema, redacta un párrafo donde resumas los conceptos relevantes
y su importancia en el contexto del aprendizaje geomorfológico,
indicando en cada caso los aportes que se hacen o pueden hacer desde la
geografía física. Reserva dicho contenido para que te sirva en el
informe final (no para que lo transcribas literalmente al informe final,
sólo para que te sirva de insumo).

# Ejercicio 2. Selección de cuenca, delineado

Selecciona una cuenca hidrográfica de interés. Usando un mapa
topográfico en el aula (preferible), o alternativamente [este mapa
topográfico
web](http://geofis.xyz/lm/index.php/view/map/?repository=mtnrd50k&project=mtnrd50k)
(requiere zoom a escala 1:100,000 o más detallada), dibuja encima, sin
dañar el mapa original, una red hidrográfica y el límite de una cuenca.

# Ejercicio 3. Cálculos de morfometría

## 3.1 Densidad de drenaje

Calcula la **densidad de drenaje** de la cuenca utilizando la fórmula:

$$
D = \frac{L_{total}}{A}
$$

Donde: - $D$ es la densidad de drenaje (km/km²), - $L_{total}$ es la
longitud total de los ríos de todos los órdenes (km), - $A$ es el área
de la cuenca (km²).

## 3.2 Obtención del orden de red

Asigna la jerarquía hidrográfica a los cursos de tu red dibujada
utilizando el método de **Strahler**, para determinar el orden de red
máximo. Indica cuántos ríos corresponden a cada orden.

## 3.3 Cálculo de la razón de bifurcación

La **razón de bifurcación** se refiere a la relación entre el número de
ríos de un determinado orden con el número de ríos del siguiente orden
superior. Según Horton (1945), esta razón es una medida importante para
entender la estructura de la red fluvial.

La fórmula de Horton para calcular la razón de bifurcación ($R_b$) es:

$$
R_b = \frac{N_n}{N_{n+1}}
$$

Donde: - $N_n$ es el número de ríos de orden $n$, - $N_{n+1}$ es el
número de ríos de orden $n+1$.

### Pasos para el cálculo

1.  **Identificación de órdenes**: Clasifica todos los ríos de la cuenca
    utilizando el método de Strahler.
2.  **Conteo de ríos**: Cuenta el número de ríos para cada orden.
3.  **Aplicación de la fórmula**: Aplica la fórmula de Horton para
    calcular la razón de bifurcación entre los diferentes órdenes.

### Ejemplo de cálculo

Supongamos que has identificado los siguientes números de ríos para cada
orden:

- **Orden 1**: 15 ríos
- **Orden 2**: 7 ríos
- **Orden 3**: 3 ríos
- **Orden 4**: 1 río

Usando la fórmula de Horton:

Para los órdenes 1 y 2:

$$
R_b = \frac{15}{7} = 2.14
$$

Para los órdenes 2 y 3:

$$
R_b = \frac{7}{3} = 2.33
$$

Para los órdenes 3 y 4:

$$
R_b = \frac{3}{1} = 3.00
$$

Existe una razón promedio también, que se obtiene promediando los
valores anteriores. También se puede estimar la razón de bifurcación
utilizando el método de regresión lineal.

# Ejercicio 4. Análisis crítico

## 4.1 Interpretación

Reflexiona sobre los resultados obtenidos y discútelos en función de los
conceptos estudiados en los libros. Responde las preguntas a
continuación, y reserva tus respuestas para el informe final.

- ¿Cómo influye el clima en la morfometría de la cuenca?
- ¿Qué impacto tiene la litología en la estructura de los sistemas
  fluviales?
- ¿Qué efectos tienen las actividades humanas sobre los procesos
  fluviales en la cuenca?

## 4.2 Influencia de Factores Externos

Reflexiona sobre cómo las variables climáticas y tectónicas podrían
haber influido en la evolución de la cuenca. Relaciona esto con las
ideas presentadas en los textos consultados.

# Informe final

Redacta un informe final de cuatro párrafos donde resumas tus hallazgos
en los ejercicios anteriores. El informe debe contener los siguientes
elementos:

- Introducción, que incluya objetivos y justificación.
- Breve descripción de la cuenca seleccionada.
- Metodología empleada, que deberá incluir los materiales y explicación
  de los cálculos realizados.
- Discusión de los resultados, donde intepretes lo obtenido e indiques
  las limitaciones y posibles estudios futuros.

El informe debe estar bien estructurado y utilizar adecuadamente las
referencias bibliográficas.

# Referencias

- Gutiérrez Elorza, M. (2008). Geomorfología. España: Pearson Educación.
- Pedraza, J. d., Carrasco González, R. M. (1996). Geomorfología:
  principios, métodos y aplicaciones. España: Rueda.

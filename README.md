# TRANFOMADA DE LA PLACE 
La Transformada de Laplace es una herramienta matemática que convierte una función en el dominio del tiempo F(t) en una función en el dominio de la frecuencia
## 1. Sistema 
Un sistema es una combinación de componentes que actúan conjuntamente para alcanzar un objetivo específico. La combinación de componentes se puede representar por medio de reglas o principios que relacionan salidas con las entradas

## 2. sistema dinamico 
•Un sistema se llama dinámico si su salida en el presente depende de una entrada en el pasado
• Si su salida en curso depende solamente de la entrada en curso, el sistema se conoce como estático.
## 3.PLANTA 
Es todo lo físico que permite que se lleve a cabo un proceso Puede ser representado matemáticamente 
Puede ser representado a través de uno o varios sistemas
### 3.1. PROCESO 
• Es la secuencia de pasos que permite el desarrollo, o fabricación de un objetivo o producto
• En el área de control se usa como sinónimo de planta
(Aunque en sentido estricto no lo son)

### 3.2.Modelos dinámicos
En control interesa obtener un modelo matemático que relacione las variables de interés con el tiempo
Hay cambios de la variable con respecto al tiempo  
Es necesario cuantificar cuanto cambia las variables de
interés con respecto al tiempo

### 3.3. Recordando cálculo diferencial
Definición de la derivada
![Texto alternativo](https://tse4.mm.bing.net/th?id=OIP.-LuSWG5JSTpbRCnBwK-gtQHaE2&pid=Api&P=0&h=180)

### 3.4. Sistemas lineales y no lineales
• Un Sistema se considera lineal cuando cumple con el principio
de superposición
• La respuesta de un Sistema al que se le aplican 2 o más
excitaciones simultáneas, es la suma de las respuestas
individuales
• Un Sistema lineal Tambien tiene la característica de
proporcionalidad entre la entrada y la salida
• Los sistemas no lineales no cumplen con el principio de
superposición
• Los sistemas no lineales se linealizan en un punto de
operación, en el cual se cumple el principio de superposición

### 3.5. Influencia de parámetros
![Texto alternativo](https://ecuaciondiferencialejerciciosresueltos.com/wp-content/uploads/2020/09/InterseccionIntegralesImpropias.png)

### 3.6. Transformada Inversa de Laplace
La Transformada Inversa de Laplace nos permite recuperar funciones en el dominio del tiempo a partir de su expresión en el dominio de la frecuencia. Se puede calcular con tablas, fracciones parciales o el método del residuo.
![Texto alternativo](https://i.ytimg.com/vi/Tjsv03Lvnoc/maxresdefault.jpg)


## 4. Ejemplo de la Transformada de Laplace
Vamos a calcular la Transformada de Laplace de la función:
![Texto alternativo](http://3.bp.blogspot.com/-km_zgvgZ4LE/UYwaTwYkrrI/AAAAAAAAEaE/gNtEiCQIWto/s1600/INTEGRAL+DE+UNA+TRANSFORMADA+DE+LAPLACE+(2).gif)

## 5.  Ejemplo de la Transformada inversa de la place
![Texto alternativo](https://i.ytimg.com/vi/emjeF_8393A/maxresdefault.jpg)

## 6. TABLA DE LA TRANSFORMADA DE LA PLACE
![Texto alternativo](https://d20ohkaloyme4g.cloudfront.net/img/document_thumbnails/f4a69a624d915ca11b44ed307ca1bc91/thumb_1200_1553.png)

## 7.TABLA DE LA TRASFORMADA INVERSA DE LA PLACE 
![Texto alternativo](https://2.bp.blogspot.com/-KPrQWMJGu6s/WvPVoW7S_ZI/AAAAAAAACAo/CYyvXUJDFRwuObz2a_cYY9t-_hhHBBWiwCLcBGAs/s1600/Transformadas+de+Laplace+org.png)

## 8. Conclusiones
La Transformada de Laplace es una herramienta matemática fundamental en el análisis de sistemas dinámicos, ecuaciones diferenciales y circuitos eléctricos. Su principal ventaja es que convierte ecuaciones diferenciales en ecuaciones algebraicas en el dominio de𝑠 lo que facilita su resolución. Es ampliamente utilizado en ingeniería, física y matemáticas aplicadas para modelar y resolver problemas complejos.
Por otro lado, la Transformada Inversa de Laplace permite regresar del dominio des sal dominio del tiempo𝑎 recuperando la función original. Esto es esencial para interpretar soluciones en términos físicos y prácticos, especialmente en la respuesta temporal de sistemas.


# Cálculo de Transformada inversa
El cálculo de la transformada inversa de Laplace es el proceso de encontrar la función original en el dominio del tiempo, , a partir de su representación en el dominio de Laplace

## 1. Transformada inversa
• Si las funciones son simples utilizar la tabla de transformadas
• Si las funciones son una combinación o una composición de varias funciones
• Calcular la integral de la definición de la transformada inversa de LaPlace
• Realizar una expansión en fracciones parciales para obtener una suma de funciones mucho más simples que se puedan encontrar en las tablas de transformadas

## 2. Descomposición en fracciones parciales
![Texto alternativo](https://0.academia-photos.com/attachment_thumbnails/37215891/mini_magick20190304-8768-2no8y8.png?1551735051)

## 3. Descomposicion en fracciones parciales
![Texto alternativo](https://study.com/cimages/multimages/16/eparfra1a.png)

# 4. Ejemplo 
![Texto alternativo](https://slideplayer.es/slide/12201957/72/images/6/Descomposici%C3%B3n+en+fracciones+parciales.jpg)
![Texto alternativo](https://slideplayer.es/slide/12201957/72/images/8/Descomposici%C3%B3n+en+fracciones+parciales.jpg)


#  Solución ecuaciones diferenciales
Una ecuación diferencial es una ecuación que relaciona una función desconocida con sus derivadas. La solución de una ecuación diferencial es la función que satisface la ecuación.
En otras palabras, una ecuación diferencial es una ecuación que describe cómo cambia una cantidad con respecto a otra variable, y la solución es la función que describe la relación entre esas variables.

## 1. Transformada inversa (Método resumido)
Paso 1: Aplicar la transformada de Laplace
Se aplica la transformada de Laplace a la ecuación diferencial para obtener una ecuación algebraica en el dominio de la frecuencia.

Paso 2: Resolver la ecuación algebraica
Se resuelve la ecuación algebraica en el dominio de la frecuencia para obtener la función de transferencia.

Paso 3: Aplicar la transformada inversa de Laplace
Se aplica la transformada inversa de Laplace a la función de transferencia para obtener la solución en el dominio del tiempo.

## 2. caso 1 Raíces reales diferentes
Si la función de transferencia F(s) tiene raíces reales diferentes, es decir:
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F(s) = (s - r_{1})(s - r_{2})(s - r_{1})"><img src="http://www.alciro.org/cgi/tex.cgi?F(s) = (s - r_{1})(s - r_{2})(s - r_{1})" title="F(s) = (s - r_{1})(s - r_{2})(s - r_{1})" border="0" /></a>
![Texto alternativo](https://static.eduboom.es/eduboom_es/uploads/vidimgs/07062021-Raices-de-numeros-reales-Radicales.jpg)

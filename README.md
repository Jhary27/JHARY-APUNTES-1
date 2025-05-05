### Función de transferencia

La función de transferencia es una herramienta matemática que se usa principalmente en ingeniería de control y procesamiento de señales para describir cómo un sistema responde a una entrada. Representa la relación entre la salida y la entrada de un sistema lineal e invariante en el tiempo, en el dominio de la frecuencia (normalmente usando la transformada de Laplace)

![Función de transferencia](https://latex.codecogs.com/svg.image?H(s)=\frac{X(s)}{Y(s)})
𝑂𝐽𝑂: 𝐸𝑠𝑡𝑜 𝑠ó𝑙𝑜 𝑎𝑝𝑙𝑖𝑐𝑎 𝑐𝑢𝑎𝑛𝑑𝑜 𝑠𝑒 𝑣𝑎𝑛 𝑎
ℎ𝑎𝑐𝑒𝑟 𝑓𝑢𝑛𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 𝑡𝑟𝑎𝑛𝑠𝑓𝑒𝑟𝑒𝑛𝑐𝑖𝑎, 𝑒𝑛 𝑒𝑙
𝑐𝑎𝑠𝑜 𝑑𝑒 𝑞𝑢𝑒𝑟𝑒𝑟 𝑠𝑜𝑙𝑢𝑐𝑖𝑜𝑛𝑎𝑟 𝑙𝑎 𝑒𝑐𝑢𝑎𝑐𝑖ó𝑛
𝑑𝑖𝑓𝑒𝑟𝑒𝑛𝑐𝑖𝑎𝑙 𝑠𝑖 𝑠𝑜𝑛 𝑛𝑒𝑐𝑒𝑠𝑎𝑟𝑖𝑎𝑠 𝑙𝑎𝑠
𝑐𝑜𝑛𝑑𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑖𝑛𝑖𝑐𝑖𝑎𝑙𝑒𝑠 𝑦 𝑛𝑜
𝑛𝑒𝑐𝑒𝑠𝑎𝑟𝑖𝑎𝑚𝑒𝑛𝑡𝑒 𝑠𝑜𝑛 0

## Clasificación de las funciones de transferencia
Una función de transferencia se puede expresar como

![Función G(s)](https://latex.codecogs.com/svg.image?G(s)=\frac{N(s)}{D(s)})
• Donde N(s) Y D(s) son polinomios en la variable “s”
• Si denominamos n al grado del polinomio del numerador
• Si denominamos m al grado del polinomio del denominador
• Se tienen 3 casos posibles:
n>m impropia
m>n estrictamente propia
n=m bipropia

## Zeros de una función de transferencia
• Si se iguala N(s) a 0 se obtienen los valores de “s” que
cumplen con la condición
• Si el numerador se hace 0 toda la función de
transferencia se vuelve cero de ahí el nombre para estos
valores de “s”
• Estos valores pueden ser reales o complejos por lo tanto
se pueden ubicar en un plano cartesiano

## Hallar los zeros de una función de transferencia

![Función G(s)](https://latex.codecogs.com/svg.image?G(s)=\frac{y(s)}{u(s)}=\frac{3(s)-1}{s^{2}+3s+2}=\frac{N(s)}{D(s)})

![N(s)](https://latex.codecogs.com/svg.image?N(s)=0)

![Ecuación](https://latex.codecogs.com/svg.image?3s-1=0)

![Resultado de s](https://latex.codecogs.com/svg.image?s=\frac{1}{3})


## Ejemplo

![Transfer Function](https://latex.codecogs.com/svg.image?H(s)=\frac{s+2}{s^{2}+3s+2})

![image](https://github.com/user-attachments/assets/2441a9c8-16d0-4f7c-9e8c-133d047d71cc)

###  Polos de una función de transferencia

• Si se iguala D(s) a 0 se obtienen los valores de “s” que
cumplen con la condición
• Si el denominador se hace 0 toda la función de
transferencia se vuelve infinito de ahí el nombre para
estos valores de “s”
• Estos valores pueden ser reales o complejos por lo tanto
se pueden ubicar en un plano cartesiano

![Transfer Function](https://latex.codecogs.com/svg.image?H(s)=\frac{N(s)}{D(s)}=\frac{b_{m}s^{m}+\cdots+b_{1}s+b_{0}}{a_{n}s^{n}+\cdots+a_{1}s+a_{0}})

## Ubicación de polosos
![image](https://github.com/user-attachments/assets/52209a72-b485-479c-895e-72bf6f0f8e5a)

### Ejemplo 
• Hallar los polos de la siguiente función de transferencia:

![Transfer Function](https://latex.codecogs.com/svg.image?H(s)=\frac{s+2}{(s+3)(s^{2}+0.5s+1)})

![Transfer Function](https://latex.codecogs.com/svg.image?(s+3)(s^{2}+0.5s+1)=0&space;)

![Transfer Function](https://latex.codecogs.com/svg.image?s+3=0\Rightarrow&space;s=3&space;)

![Transfer Function](https://latex.codecogs.com/svg.image?s^{2}+0.5s+1=0&space;)

![Transfer Function](https://latex.codecogs.com/svg.image?s=\frac{-0.5\pm\sqrt{(0.5)^2-4(1)(1)}}{2(1)}=\frac{-0.5\pm\sqrt{0.25-4}}{2}=\frac{-0.5\pm\sqrt{-3.75}}{2})

![Transfer Function](https://latex.codecogs.com/svg.image?s=\frac{-0.5\pm%20j\sqrt{3.75}}{2}=\frac{-0.5\pm%20j1.936}{2}=-0.25\pm%20j0.968)

### Grado de una función de transferencia
• Otra forma de clasificar las funciones de transferencia es
por su orden o grado
• Esto lo define el polinomio característisco

## Teorema del valor final
• El error en estado estacionario corresponde al error
medido en 𝑡 = ∞
• Es posible aprovechar el teorema del valor final para
saber el valor final del error

### EJEMPLO
![Transfer Function](https://latex.codecogs.com/svg.image?F(s)=\frac{5}{s(s+2)})

![Transfer Function](https://latex.codecogs.com/svg.image?\displaystyle\lim_{t\to&space;0}f(t)=\displaystyle\lim_{s\to&space;0}s.\frac{5}{s(s+2)5)

![Transfer Function](https://latex.codecogs.com/svg.image?=\frac{5}{2})

![image](https://github.com/user-attachments/assets/57843cae-2dda-4049-aaaa-febdda9b5977)

### Respuesta de un sistema
• Sería necesario modelar cada Sistema desde cero
![image](https://github.com/user-attachments/assets/04f8626c-0e76-4381-b650-0eac1976548c)
* Si se tuviera en
cuenta las señales
reales
* Ruido,
Diferentes rangos,
Diferentes señales
### Posibles entradas de un sistema
• Si la solución de una ecuación diferencial depende de la
entrada, la respuesta de un Sistema También
• Es muy difícil conocer la señales que están ocurriendo en
un Sistema ya que depende de muchos factores como
ruido, tipo de señales, ambiente , entre otras
• Además el Sistema de control debe diseñarse para que
funcione ante cualquier señal
• En control se utilizan diferentes tipos de señales de prueba
para evaluar el desempeño de un sistema

## Entrada Escalón
• Es una entrada que considera un cambio de nivel
repentino

![image](https://github.com/user-attachments/assets/22657de5-566f-4d97-bbe0-a8873b79c3e8)

### Modelamiento de sistemas condiagramas de bloques 
### Modelos de sistemas complejos

• Se podrían modelar sistemas como un todo hallando las
funciones de transferencia de cada componente
• Otro enfoque es utilizar modelos ya desarrollados
ampliamente para construir modelos más complejos
• Aún usando este enfoque hay muchos tipos de procesos
y dispositivos

## Solenoide 
Un solenoide está formado por un circuito eléctrico, un acoplamiento electromecánico (transductor) y un
sistema mecánico de traslación

![Transfer Function](https://latex.codecogs.com/svg.image?L\frac{di}{dt}+Ri=v(t))

![Transfer Function](https://latex.codecogs.com/svg.image?I(S)=V(S)\frac{1}{Ls+R})

![image](https://github.com/user-attachments/assets/44b5a658-99c0-436b-89f7-99f6e8f02d43)

## Solenoide
• El electroimán produce una fuerza mecánica proporcional a la corriente en el embobinad

![Transfer Function](https://latex.codecogs.com/svg.image?f_{s}=k_{s}i)

![Transfer Function](https://latex.codecogs.com/svg.image?f_{s}=k_{s}i(s))

![image](https://github.com/user-attachments/assets/44b5a658-99c0-436b-89f7-99f6e8f02d43)
Acople entre la parte electromagnética y la parte mecánica

## Solenoide
• El electroimán atrae una masa acoplada por medio de un resorte y se considera el mortiguamiento dado por la
envolvente de la bobina

![Transfer Function](https://latex.codecogs.com/svg.image?m\frac{d^{2}x}{dt^{2}}+b\frac{dx}{dt}kx=f(t))

![Transfer Function](https://latex.codecogs.com/svg.image?X(s)=F(s)\frac{1}{ms^{2}+bs+k})

![image](https://github.com/user-attachments/assets/9f3f8513-754a-4ff3-b071-a53b9ded13ca)

## Motor DC
![image](https://github.com/user-attachments/assets/54de4187-1ba4-44bf-8ad6-094c63ec6bcb)

## Motor DC (Corriente de campo)
• Circuito electromagnético:
![image](https://github.com/user-attachments/assets/07afb975-9d06-42aa-aacc-05f3af54f384)

 ![Transfer Function](https://latex.codecogs.com/svg.image?L_{C}\frac{di_{c}}{dt}+R_{c}i_{c}=v_{c}(t))

 ![Transfer Function](https://latex.codecogs.com/svg.image?I_{C}(s)=V_{c(s)}\frac{1}{(sL_{c}+R_{c})})

![image](https://github.com/user-attachments/assets/44b5a658-99c0-436b-89f7-99f6e8f02d43)

## Motor DC (Corriente de campo)
• El flujo Φ en el entrehierro es proporcional a la corriente de campo

 ![Transfer Function](https://latex.codecogs.com/svg.image?\phi=K_{c}i_{c})
 

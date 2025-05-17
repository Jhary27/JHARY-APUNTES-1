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

 ## Motor DC (Corriente de campo)
 • Circuito electromagnético:

 ![image](https://github.com/user-attachments/assets/8ef12ee9-4226-4a70-b18f-43cab8329d8f)

 ![Transfer Function](https://latex.codecogs.com/svg.image?&space;L_c\frac{di_c}{dt}+R_c&space;i_c=v_c(t))
 
  ![Transfer Function](https://latex.codecogs.com/svg.image?I_c(s)=V_c(s)\cdot\frac{1}{sL_c+R_c})

  ### Motor DC (Corriente de campo)
  • El torque aplicado (parte mecánica) a la carga se comporta como un Sistema rotacional clásico que
    considera la inercia y la fricción mecánica
    
 ![Transfer Function](https://latex.codecogs.com/svg.image?J\frac{d^2\theta}{dt^2}+b\frac{d\theta}{dt}+k\theta=\tau(t))
 
  ![Transfer Function](https://latex.codecogs.com/svg.image?\Theta(s)=T_c(s)\cdot\frac{1}{s^2&space;J+bs})

  ![image](https://github.com/user-attachments/assets/419985a2-5e30-49cf-98ba-86836df5a011)

  ### Motor DC (Corriente de campo) 
   La conexión de los modelos se realiza de la siguiente manera:
   
 ![Transfer Function](https://latex.codecogs.com/svg.image?\Theta(s)=V_c(s)\cdot\frac{K_m}{(sL_c+R_c)(Js^2+bs)}-T_p(s)\cdot\frac{1}{Js^2+bs})

 ![Transfer Function](https://latex.codecogs.com/svg.image?\frac{\Theta(s)}{V_c(s)}=\frac{K_m}{(sL_c+R_c)(Js^2+bs)})

 ![image](https://github.com/user-attachments/assets/f002f084-03f4-4c4a-9f26-274f8b609e2a)

 ### Motor DC (Corriente de armadura)
 
 El voltaje inducido en la armadura es proporcional a la velocidad angular del eje
 
 ![Transfer Function](https://latex.codecogs.com/svg.image?V_a(s)=(sL_a+R_a)I_a(s)+V_b(s))

  ![Transfer Function](https://latex.codecogs.com/svg.image?V_b(s)=K_b\omega(s))
  
• Combinando estas ecuaciones se obtiene

 ![Transfer Function](https://latex.codecogs.com/svg.image?I_a(s)=\frac{V_a(s)-K_b\omega(s)}{sL_a+R_a})

 ![image](https://github.com/user-attachments/assets/575dbbfa-abf6-4b4a-8a1d-b4b37b8db810)

 ### Elementos Transmisores de energía

 ### Engranajes y Poleas
Son dispositivos mecánicos que transmiten la energía desde una parte del sistema a otra

![image](https://github.com/user-attachments/assets/1efb58ed-7476-4c1b-839f-043e281f0d89)

 ![Transfer Function](https://latex.codecogs.com/svg.image?\frac{\tau_2}{\tau_1}=\frac{N_2}{N_1})

 ![Transfer Function](https://latex.codecogs.com/svg.image?\Theta(s)=V_c(s)\cdot\frac{K_m}{(sL_c+R_c)(Js^2+bs)}-T_p(s)\cdot\frac{1}{Js^2+bs})

 ![Transfer Function](https://latex.codecogs.com/svg.image?\frac{\Theta(s)}{V_c(s)}=\frac{K_m}{(sL_c+R_c)(Js^2+bs)})
  
 ![Transfer Function](https://latex.codecogs.com/svg.image?\beta_{\text{equiv}}=\left(\frac{N_1}{N_2}\right)^2\beta&space;)

### Diagrama de bloques
![image](https://github.com/user-attachments/assets/c2f2eaf0-dfc7-4d17-a1d1-ea2d424c374e)

### Palancas

![image](https://github.com/user-attachments/assets/ce8f388e-e7bc-43af-b12d-6bb537078892)

![Transfer Function](https://latex.codecogs.com/svg.image?\frac{-f_2}{f_1}=\frac{d_1}{d_2}\quad\text{y}\quad\frac{d_1}{d_2}=\frac{-x_1}{x_2})

### Potenciómetro de rotación

![image](https://github.com/user-attachments/assets/b65e7473-c52d-4ac1-a610-6264a33d3eb2)

![Transfer Function](https://latex.codecogs.com/svg.image?V_o=\frac{\theta}{\theta_{\text{m&space;x}}}V_{\alpha})

![image](https://github.com/user-attachments/assets/461a88ff-9e68-4614-ad53-46e29ecb8405)

### Tacómetros
Son dispositivos que convierten la velocidad angular a voltaje

![image](https://github.com/user-attachments/assets/47b314f1-b8a9-4b4c-bf5f-9127dcb8505f)

![Transfer Function](https://latex.codecogs.com/svg.image?v(t)=k\frac{d\theta(t)}{dt})

![Transfer Function](https://latex.codecogs.com/svg.image?G(s)=\frac{V(s)}{\Theta(s)}=ks&space;)

### Sensores transmisores

![image](https://github.com/user-attachments/assets/cdce7940-af06-4e6b-a4d6-e7895de024a2)

• Si son lineales:
• Si no son lineales:

### Modelos de otros procesos

• Sea un tanque lleno con ocho litros de agua salada en el cual están disueltos dos kg de sal. Una solución de salmuera (agua salada) con tres kg de sal por litro entra al
tanque a una velocidad de 4 l/min, mientras la mezcla bien agitada sale a la misma velocidad con la que entra.


![image](https://github.com/user-attachments/assets/9e54e54b-f26b-4283-89b8-cc1ab99c171d)

### Sistema Térmico

![image](https://github.com/user-attachments/assets/5c355eb3-16fb-418e-b5ee-be73f3147545)

### Álgebra de Bloques
Una herramienta que puede ayudar a entender un poco la interacción entre varios sistemas son los diagramas de
bloques
 Primer sistema de control J. Watt
Para explicar su sistema empezó a desarrollar los diagramas de bloques

![image](https://github.com/user-attachments/assets/4867f502-9fda-4cbd-9db6-5f1927526ce9)

### Elementos de un diagrama de bloques

• Bloque Funcional: es un símbolo para representar la operación matemática que sobre la señal de entrada
hace el bloque para producir la salida

![image](https://github.com/user-attachments/assets/a244b14f-f014-4a23-8b29-09d1ccaa3f47)

### Elementos de un diagrama de bloques
• Flechas: Representa las señales dentro del proceso. Obsérvese que la señal sólo puede pasar en la dirección
de las flechas. Por tanto, un diagrama de bloques de un sistema de control muestra explícitamente una propiedad
unilateral. La punta de flecha que señala el bloque indica la entrada, y la punta de flecha que se aleja del bloque
representa la salida. Tales flechas se conocen como  señales

![image](https://github.com/user-attachments/assets/1c94fe46-8e49-47ef-a646-316fabab18c0)

### Elementos de un diagrama de bloques

• Punto Suma: Realiza operaciones (suma o resta) entre señales únicamente. El signo más o el signo menos en
cada punta de flecha indica si la señal debe sumarse o restarse. Es importante que las cantidades que se sumen
o resten tengan las mismas dimensiones y las mismas unidades.

![image](https://github.com/user-attachments/assets/9e551846-fb03-4088-aa17-8d5cf0e49122)

### Ramificación
• Un punto de ramificación es aquel a partir del cual la
señal de un bloque va de modo concurrente a otros bloques o puntos de suma

 ![image](https://github.com/user-attachments/assets/42df167e-c39b-4dd1-9512-9fe751702e94)

### Interpretación del diagrama
• La salida de un bloque funcional corresponde a la señal
de entrada (Dominio s) multiplicada por por la función de transferencia del bloque.

![image](https://github.com/user-attachments/assets/a1ba426e-e3ae-4c2d-bf1e-b10759dfadc8)

### Bloques en cascada
• Si se tienen 2 sistemas interconectados

![image](https://github.com/user-attachments/assets/0d5d8f61-3a5f-44d3-a32c-e34872ac93cd)

![image](https://github.com/user-attachments/assets/c3abe28d-6eed-47c1-9f86-3144b8f9b197)


### Aplicación de un diagrama de bloques

![image](https://github.com/user-attachments/assets/77567502-2dcb-432a-ae1b-32d218ca2728)

![image](https://github.com/user-attachments/assets/413a288e-7a4f-4bea-8ae7-392fa9a23d22)

### Algebra de bloques

Utilizando algebra de bloques es posible obtener la función de transferencia de
sistemas compuestos de varios bloques funcionales

![image](https://github.com/user-attachments/assets/2e4bfbc3-2d08-49fe-be51-1d1e6aeb872f)

### Lazo de realimentación positivo

![image](https://github.com/user-attachments/assets/196eb20b-2ced-4860-bee1-8b2523d0c53a)

### Reducción de diagramas

### Aplicación algebra de bloques
• Hallar la función de transferencia

![image](https://github.com/user-attachments/assets/5cb30882-0090-4267-9c21-bd66ca639adc)

### Aplicando algebra de bloques

![image](https://github.com/user-attachments/assets/563e46b6-0a2f-4de0-96e1-d898e42fc77c)

### diagrama de flujo  de señales
 Este tipo de diagramas permite otra formas  de representacion de sistemas mas complejos 
 Se  utiliza  para obtener de una manera mas sencilla la funcion de transfericia total del sistema 

<img width="161" alt="image" src="https://github.com/user-attachments/assets/9c807073-008b-4599-a2b6-39a39e9e1b0b" />

### Deficion 
- camino o trayectoria: es un recorrido de ramas conectadas en el sentido de la flechas de las ramas
-  si no se cruza el nodo ams de una vez, el camino o trayectoria es abiero
-  si el camino o la trayectoria finaliza  en el mismo nodo  de la cual partio, y no cruza ninguna otra mas y no cruza ninguno otro mas

 <img width="123" alt="image" src="https://github.com/user-attachments/assets/01a27c84-8cce-461e-9697-593fd29d1483" />

### Formula del maso 
  
![Transfer Function](https://latex.codecogs.com/svg.image?&space;P=\frac{1}{\Delta}\sum_i&space;P_i\Delta_i&space;) 

Pk: Ganancia de los caminos directos.

Δ = 1 – (suma de ganancias de los lazos) + (suma del producto de 2 lazos que no se tocan) – (suma del producto de 3 lazos que no se tocan) + …

Δk = 1 – (suma de ganancias de los lazos que no toquen la trayectoria Pk) + (suma de productos de 2 lazos que no toquen la trayectoria Pk y no se toquen entre sí) – (suma de productos de 3 lazos que no toquen la trayectoria Pk y no se toquen entre sí) + 

### EJEMPLO 

- trayectoria directa
   
![Transfer Function](P_1=1&plus;G_1,\quad&space;G_2&plus;G_2&plus;1=G_1&space;G_2&space;G_3&space;)

- lazos cerrados
  
![Transfer Function](https://latex.codecogs.com/svg.image?L_1=G_2&space;G_3&space;H_1\\L_2=-G_2&space;G_3&space;H_2\\L_3=-G_1&space;G_3&space;H_1&space;)

- Determinate

![Transfer Function](https://latex.codecogs.com/svg.image?\Delta=1-(L_1&plus;L_2&plus;L_3))

- cofactores 
  
![Transfer Function](https://latex.codecogs.com/svg.image?\Delta_1=1&space;)

- funcion de tranferecia

![Transfer Function](https://latex.codecogs.com/svg.image?\frac{C(s)}{R(s)}=\frac{P_1\Delta_1}{\Delta}=\frac{G_1&space;G_2&space;G_3}{G_2&space;G_3&space;H_1&plus;G_2&space;G_3&space;H_2&plus;G_1&space;G_3&space;H_1})

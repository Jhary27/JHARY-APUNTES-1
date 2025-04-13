# Energía potencial
• En los sistemas mecánicos la energía potencial cambia
de acuerdo a su posición (con respecto a una referencia)
• En los sistemas mecánicos los resortes y las masas
almacenan energía potencial
• La energía potencial es equivalente al trabajo realizado
por la fuerza externa
## formula
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{avg} = V_{rms} \cdot I_{rms} \cdot \cos(\phi) ">
<img src="http://www.alciro.org/cgi/tex.cgi?P_{avg} = V_{rms} \cdot I_{rms} \cdot \cos(\phi) " title="P_{avg} = V_{rms} \cdot I_{rms} \cdot \cos(\phi) " border="0" /></a>

## Energía cinética
• La energía cinética es debida a la velocidad
• Solamente los elementos de inercia pueden almacenar
energía cinética
## formula 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=E_k = \frac{1}{2} J \omega^2 "><img src="http://www.alciro.org/cgi/tex.cgi?E_k = \frac{1}{2} J \omega^2 " title="E_k = \frac{1}{2} J \omega^2 " border="0" /></a>

## Potencia
• La realización de trabajo que varía con respecto al
tiempo
## formula 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P(t) = F(t) \cdot v(t) ">
<img src="http://www.alciro.org/cgi/tex.cgi?P(t) = F(t) \cdot v(t) " title="P(t) = F(t) \cdot v(t) " border="0" /></a>

###  Energía potencial en un resorte
Es el trabajo neto hecho sobre él por las fuerzas que
actúan en sus extremos cuando es comprimido o estirado
• De forma general el cambio de energía sería:

## formula 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=E_p = \frac{1}{2} \cdot 200 \cdot (0.1)^2 = 1 \, \text{J}"><img src="http://www.alciro.org/cgi/tex.cgi?E_p = \frac{1}{2} \cdot 200 \cdot (0.1)^2 = 1 \, \text{J}" title="E_p = \frac{1}{2} \cdot 200 \cdot (0.1)^2 = 1 \, \text{J}" border="0" /></a>

### Potencia en un resorte 
• Potencia requerida para estirar o comprimir un resorte
## formula 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P(t) = -200 \cdot 0.1 \cdot 0.2 = -4 \, \text{W} ">
<img src="http://www.alciro.org/cgi/tex.cgi?P(t) = -200 \cdot 0.1 \cdot 0.2 = -4 \, \text{W} " title="P(t) = -200 \cdot 0.1 \cdot 0.2 = -4 \, \text{W} " border="0" /></a>

### Potencia en una masa
• La potencia requerida para acelerar una masa en línea
recta
## formula 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F(t) = m \cdot a(t) ">
<img src="http://www.alciro.org/cgi/tex.cgi?F(t) = m \cdot a(t) " title="F(t) = m \cdot a(t) " border="0" /></a>

### Energía disipada
• La energía disipada en un amortiguador corresponde al
trabajo neto realizado sobre este
## formula 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=E = \int_{0}^{t} P(t) \, dt = \int_{0}^{t} c \cdot v(t)^2 \, dt"><img src="http://www.alciro.org/cgi/tex.cgi?E = \int_{0}^{t} P(t) \, dt = \int_{0}^{t} c \cdot v(t)^2 \, dt" title="E = \int_{0}^{t} P(t) \, dt = \int_{0}^{t} c \cdot v(t)^2 \, dt" border="0" /></a>

### Potencia disipada en amortiguador
• La potencia disipada en el amortiguador de cilindro es:

### Conservación de energía
• Es posible obtener el modelo matemático considerando
que la energía total de un sistema permanece igual si
ninguna energía entra o sale del sistema
• En los sistemas mecánicos la fricción disipa energía en
forma de calor
• Los sistemas que ni incluyen fricción se denominan
sistemas conservativos


### Sistema conservativo
• Toda la energía (cinética y potencial) sale del sistema en
forma de trabajo mecánico. No se disipa energía

###  trabajo 2
Se desea modelar un brazo robótico como el de la figura, considerando como entrada el torque del motor y como salida la velocidad angular del brazo. Considere 𝐽𝑚 = 0,𝐽𝐿 = 0,𝐾 = 0.5,𝐵𝑚 = 0.1 𝑦 𝐵𝐿 = 0.3 
a. Halle la función de transferencia 𝜔𝐿/𝑇𝑚 
b. Indique cual es la constante de tiempo y la ganancia estática del sistema
 c. Suponga que el motor tiene una ganancia estática de 0.1. Si se aplica un escalón de 5 V al motor que velocidad angular se espera en el brazo en estado estacionario?
 d. Solucione la ecuación diferencial utilizando ODE45 de Matlab y explique el resultado obtenido comparando con el movimiento 
![1000104115](https://github.com/user-attachments/assets/0262c016-c89a-4ce3-8c61-d5890840808c)
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L\dot{\omega}_L + (B_m + B_L)\omega_L + K\theta_L = T_m" ><img src="http://www.alciro.org/cgi/tex.cgi?L\dot{\omega}_L + (B_m + B_L)\omega_L + K\theta_L = T_m" title="L\dot{\omega}_L + (B_m + B_L)\omega_L + K\theta_L = T_m" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\theta_L = \int \omega_L \, dt"><img src="http://www.alciro.org/cgi/tex.cgi?\theta_L = \int \omega_L \, dt" title="\theta_L = \int \omega_L \, dt" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J_L\ddot{\theta}_L + (B_m + B_L)\dot{\theta}_L + K\theta_L = T_m "><img src="http://www.alciro.org/cgi/tex.cgi?J_L\ddot{\theta}_L + (B_m + B_L)\dot{\theta}_L + K\theta_L = T_m " title="J_L\ddot{\theta}_L + (B_m + B_L)\dot{\theta}_L + K\theta_L = T_m " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J_L\dot{\omega}_L + (B_m + B_L)\omega_L + K\int \omega_L \, dt = T_m "><img src="http://www.alciro.org/cgi/tex.cgi?J_L\dot{\omega}_L + (B_m + B_L)\omega_L + K\int \omega_L \, dt = T_m " title="J_L\dot{\omega}_L + (B_m + B_L)\omega_L + K\int \omega_L \, dt = T_m " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J_L s\Omega_L(s) + (B_m + B_L)\Omega_L(s) + \frac{K}{s} \Omega_L(s) = T_m(s) "><img src="http://www.alciro.org/cgi/tex.cgi?J_L s\Omega_L(s) + (B_m + B_L)\Omega_L(s) + \frac{K}{s} \Omega_L(s) = T_m(s) " title="J_L s\Omega_L(s) + (B_m + B_L)\Omega_L(s) + \frac{K}{s} \Omega_L(s) = T_m(s) " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Omega_L(s) \left(J_L s^2 + (B_m + B_L)s + K\right) = s T_m(s) ">
<img src="http://www.alciro.org/cgi/tex.cgi?\Omega_L(s) \left(J_L s^2 + (B_m + B_L)s + K\right) = s T_m(s) " title="\Omega_L(s) \left(J_L s^2 + (B_m + B_L)s + K\right) = s T_m(s) " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{\Omega_L(s)}{T_m(s)} = \frac{s}{0.5s^2 + 0.4s + 0.5} "><img src="http://www.alciro.org/cgi/tex.cgi?\frac{\Omega_L(s)}{T_m(s)} = \frac{s}{0.5s^2 + 0.4s + 0.5} " title="\frac{\Omega_L(s)}{T_m(s)} = \frac{s}{0.5s^2 + 0.4s + 0.5} " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=H(s) = \frac{s}{J_L s^2 + B_{eq}s + K} ">
<img src="http://www.alciro.org/cgi/tex.cgi?H(s) = \frac{s}{J_L s^2 + B_{eq}s + K} " title="H(s) = \frac{s}{J_L s^2 + B_{eq}s + K} " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J_L s^2 + B_{eq}s + K = 0 "><img src="http://www.alciro.org/cgi/tex.cgi?J_L s^2 + B_{eq}s + K = 0 " title="J_L s^2 + B_{eq}s + K = 0 " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\tau = \frac{J_L}{B_{eq}} = \frac{0.5}{0.4} = 1.25 \ \text{seg} ">
<img src="http://www.alciro.org/cgi/tex.cgi?\tau = \frac{J_L}{B_{eq}} = \frac{0.5}{0.4} = 1.25 \ \text{seg} " title="\tau = \frac{J_L}{B_{eq}} = \frac{0.5}{0.4} = 1.25 \ \text{seg} " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=K_{est} = \lim_{s \to 0} H(s) = 0 ">
<img src="http://www.alciro.org/cgi/tex.cgi?K_{est} = \lim_{s \to 0} H(s) = 0 " title="K_{est} = \lim_{s \to 0} H(s) = 0 " border="0" /></a>

![1000104163](https://github.com/user-attachments/assets/17a7ab93-50c6-421b-99aa-3a5bef00a379)

## código 
---

% Parámetros
Tm = 1;       % Torque motor (ejemplo)
B_eq = 0.1;   % Coef. de fricción
K = 0.5;      % Constante
J_L = 0.05;   % Momento de inercia
% Sistema
f = @(t, y) [ ...
   (Tm - B_eq * y(1) - K * y(2)) / J_L;  % dy(1)/dt = dω/dt
   y(1)                                 % dy(2)/dt = dθ/dt = ω
];
% Condiciones iniciales
y0 = [0; 0];  % [omega0; theta0]
% Intervalo de tiempo
tspan = [0 10];
% Resolver
[t, y] = ode45(f, tspan, y0);
% Extraer resultados
omega = y(:,1);
theta = y(:,2);
% Graficar
plot(t, omega, 'r', t, theta, 'b')
legend('\omega(t)', '\theta(t)')
xlabel('Tiempo [s]')
ylabel('Respuesta')
title('Sistema con integral de \omega(t)')
grid on

---

### Circuito RLC 

Un circuito RLC es un tipo de circuito eléctrico que contiene una resistencia (R), una inductancia (L) y una capacitancia (C) conectados de diferentes maneras. Este tipo de circuito se usa comúnmente para modelar sistemas oscilatorios, como filtros, circuitos resonantes y sistemas de comunicación.
![1000104135](https://github.com/user-attachments/assets/982ad9a4-a9f3-4686-90d3-9c2f529b2c6d)

## ejemplo 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\omega = 2\pi f = 2\pi \cdot 50 = 314.16 \, \text{rad/s}">
<img src="http://www.alciro.org/cgi/tex.cgi?\omega = 2\pi f = 2\pi \cdot 50 = 314.16 \, \text{rad/s}" title="\omega = 2\pi f = 2\pi \cdot 50 = 314.16 \, \text{rad/s}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Z_L = j \omega L = j \cdot 314.16 \cdot 0.5 = j157.08 \, \Omega"><img src="http://www.alciro.org/cgi/tex.cgi?Z_L = j \omega L = j \cdot 314.16 \cdot 0.5 = j157.08 \, \Omega
" title="Z_L = j \omega L = j \cdot 314.16 \cdot 0.5 = j157.08 \, \Omega
" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Z_C = \frac{1}{j\omega C} = \frac{1}{j \cdot 314.16 \cdot 20 \times 10^{-6}} = -j \cdot 159.15 \, \Omega">
<img src="http://www.alciro.org/cgi/tex.cgi?Z_C = \frac{1}{j\omega C} = \frac{1}{j \cdot 314.16 \cdot 20 \times 10^{-6}} = -j \cdot 159.15 \, \Omega" title="Z_C = \frac{1}{j\omega C} = \frac{1}{j \cdot 314.16 \cdot 20 \times 10^{-6}} = -j \cdot 159.15 \, \Omega" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Z = 10 - j2.07 \, \Omega ">
<img src="http://www.alciro.org/cgi/tex.cgi?Z = 10 - j2.07 \, \Omega " title="Z = 10 - j2.07 \, \Omega " border="0" /></a>



### Amplificador no inversor 
Es una configuración de un amplificador operacional (op-amp) en la cual la señal de entrada se aplica a la entrada no inversora (+) del op-amp. La salida del amplificador está en fase con la señal de entrada, es decir, no invierte su signo.
![1000104139](https://github.com/user-attachments/assets/b91867ce-fcf3-482f-b832-1b44752ccdbd)



### ACTIVIDAD QUE DEJO EL PROFESOR 
###  1.1 forma manual 
![1000104159](https://github.com/user-attachments/assets/a5fbea1e-3395-48b1-adfb-0a13a5e90d66)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
R_{eq} = R1 + R2 = 70 \, \Omega
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
R_{eq} = R1 + R2 = 70 \, \Omega
\] " title="\[
R_{eq} = R1 + R2 = 70 \, \Omega
\] " border="0" /></a> 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
\tau = R_{eq} \cdot C = 70 \cdot 100 \times 10^{-6} = 0.007 \, s = 7 \, \text{ms}
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
\tau = R_{eq} \cdot C = 70 \cdot 100 \times 10^{-6} = 0.007 \, s = 7 \, \text{ms}
\] " title="\[
\tau = R_{eq} \cdot C = 70 \cdot 100 \times 10^{-6} = 0.007 \, s = 7 \, \text{ms}
\] " border="0" /></a> 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
y(t) = V_f + (V_0 - V_f)e^{-t/\tau}
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
y(t) = V_f + (V_0 - V_f)e^{-t/\tau}
\] " title="\[
y(t) = V_f + (V_0 - V_f)e^{-t/\tau}
\] " border="0" /></a> 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
y(t) = V_0 e^{-t/\tau}
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
y(t) = V_0 e^{-t/\tau}
\] " title="\[
y(t) = V_0 e^{-t/\tau}
\] " border="0" /></a> 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
y(t) = 5(1 - e^{-t/0.007})
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
y(t) = 5(1 - e^{-t/0.007})
\] " title="\[
y(t) = 5(1 - e^{-t/0.007})
\] " border="0" /></a> 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
y(0.1) = 5(1 - e^{-14.29}) \approx 5 \, V
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
y(0.1) = 5(1 - e^{-14.29}) \approx 5 \, V
\] " title="\[
y(0.1) = 5(1 - e^{-14.29}) \approx 5 \, V
\] " border="0" /></a> 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\[
y(t) = 5 e^{-(t - 0.1)/0.007}
\] "><img src="http://www.alciro.org/cgi/tex.cgi?\[
y(t) = 5 e^{-(t - 0.1)/0.007}
\] " title="\[
y(t) = 5 e^{-(t - 0.1)/0.007}
\] " border="0" /></a> 

###  1.2  ode45
---
mira el código clc;
clear;
close all;

% Parámetros
R1 = 50;
R2 = 20;
C = 100e-6;
RC_total = (R1 + R2) * C;  % 0.007

% Entrada: señal cuadrada de 5 Hz y 5V
u = @(t) 5 * double(mod(floor(2*5*t),2) == 0);

% Ecuación diferencial
odefun = @(t, y) (1/RC_total)*(u(t) - y);

% Simulación
tspan = [0 1];   
y0 = 0;
[t, y] = ode45(odefun, tspan, y0);

% Graficar respuesta
plot(t, y, 'b', 'LineWidth', 2);
xlabel('Tiempo [s]');
ylabel('Voltaje en el capacitor y(t)');
title('Respuesta a señal cuadrada de 5 Hz y 5V');
grid on; 

---

###  1.3  simulink 
![1000104144](https://github.com/user-attachments/assets/58fbfb64-efec-48be-b299-f39758570271)



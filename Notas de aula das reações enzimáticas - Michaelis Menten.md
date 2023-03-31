# Notas de aula das reações enzimáticas - Michaelis Menten

31 de março de 2023

$ E + S \xrightleftharpoons[k2]{k1}ES$

$ ES \xrightharpoonup[k3]{} E + P$

balanço de massa

$ r_{ES}= \frac{d_{ES}}{dt} =k1.E.S -k2.ES -k3.ES$                (1)

$ r_{S}= \frac{d_{S}}{dt} =-k1.E.S $                                                        (2)

$ r_{P}= \frac{d_{P}}{dt} =-k3.ES $                                                          (3)

Considerando que o balanço da formação do complexo ES consumo sejam rápidos resultando $r_{ES}=0$, aplicando na equação 1

$  k1.E.S =(k2+k3).ES$                                                (4)

$\frac{{E.S}}{ES}= \frac{k2+k3}{k1}$                                                                          (5)

$\frac{k2+k3}{k1}= km$

$ES= \frac{E.S}{km}$

A concentração inicial de Enzima é $E_0$.

$E_0= E + ES$

$E_0= E + \frac{E.S}{km}$

$E_0= E .\big( 1+\frac{S}{km})$

$E= \frac{E_0} {1+ \frac{S}{km}}$

voltando para a Equação 3

$r_{P}= k3.ES$

$r_{P}= k3.\frac{E.S}{km}$

$r_{P}= -k3.\frac{E_0.S}{\big(1+\frac{S}{km}).km}$

$r_{P}= k3.\frac{E_0.S}{\big(1+\frac{S}{km}\big).km}$

$r_{P}= \frac{k3.E_0.S}{km+S}$

A concentração inicial de enzima ($E_0$) vezes a constante de reação k3 é chamado de $V_{max}$

$k3.E_0=V_{max}$

Então

$r_p=\frac{V_{max}.S}{km+S}$
